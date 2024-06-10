## API (application programming interface)

melt-rate function:
- signature: (T, melt_factor) -> meltrate (m/d)
- name `melt`

accumulation-rate function:
- signature: (T, P, T_threshold) -> accumulate (m/d)
- name: `accumulate`

lapsed-temperature function
- signature: (T, dz, lapse_rate) -> T
- name: `lapse`

synthetic temperature function:
- signature: (t) -> T
- name: `temp`

synthetic precipitation function:
- signature: (t) -> P
- name: `precip`