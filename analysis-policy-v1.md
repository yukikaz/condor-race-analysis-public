# ChatGPT Race Analysis Policy v1

Use only facts present in the race context. Separate observed facts, deterministic derived metrics, proxies, interpretation, uncertainty, and alternatives.

- Analyze `FINISHED` pilots separately from partial `LANDED`, `DNF`, `CRASHED`, or other incomplete tracks. Never place partial tracks in the finished ranking.
- Compare every leg and identify who was fastest and where time was gained or lost.
- Explain time and energy together. Do not treat the fastest isolated interval as automatically best.
- Separate circling climb from progressing lift.
- Weak climb rate alone is not evidence of poor climb selection. When weak lift
  is accepted at low AGL or low terrain-energy margin, treat it first as possible
  recovery behavior. Separate voluntary weak-lift selection at comfortable
  energy from necessary low-energy recovery. Evaluate the preceding route,
  speed, climb rejection, and energy-management decisions that caused the
  low-energy state. Do not criticize weak-lift use solely because its climb rate
  is low.
- Do not equate `SEARCH_CENTER` with thermal skill. Turning is geometry evidence, not proof of a thermal or pilot intent.
- Terrain-energy fields are proxies. DEM and GPS altitude may use different vertical datums.
- Pseudo-energy is derived from GPS altitude and ground speed, so it is wind-contaminated and is not total energy, IAS, or TAS.
- Interpret Final Glide using Required ground L/D and pseudo-energy margin together. Keep actual-route terrain constraint separate from the straight-route reference.
- Do not confuse aircraft performance configuration with pilot judgment or skill.
- Do not assert ridge, dolphin, convergence, thermal source, cloud use, safety judgment, visibility, workload, or intent when the logs cannot establish it.
- Historical samples are evidence only. Always report `sample_count`; one or two samples are examples, not a trend.
- Explain why the result occurred, not only the final rank. Preserve plausible alternative explanations.
