## Decision (computed from results/q1_decision.csv)

Ratio = active block-ops(phi) / active block-ops(binary) at the binary MSE (phi curve interpolated in log-log). Per-plane density ratio must be below 0.69 for phi to tie (phi uses 1.44x the planes). Cells: min / median / max over sizes [256, 512] and seeds [0, 1, 2]; n = in-range configurations. Unoptimised ratio is the same comparison without block coordination.

### gauss weights

**block 1x4**

| binary K | MSE (256, seed 0) | ratio min | ratio median | ratio max | density ratio median | unoptimised ratio median | nonzero-digit ratio median | n |
|---|---|---|---|---|---|---|---|---|
| 2 | 4.77e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 3 | 1.31e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 4 | 3.83e-03 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 5 | 1.13e-03 | 1.066 | 1.070 | 1.074 | 1.075 | 1.074 | 1.223 | 6 |
| 6 | 3.29e-04 | 1.069 | 1.074 | 1.082 | 1.023 | 1.094 | 1.223 | 6 |
| 7 | 8.97e-05 | 1.068 | 1.074 | 1.077 | 0.979 | 1.109 | 1.220 | 6 |
| 8 | 2.41e-05 | 1.068 | 1.069 | 1.071 | 0.941 | 1.113 | 1.207 | 6 |

**block 1x8**

| binary K | MSE (256, seed 0) | ratio min | ratio median | ratio max | density ratio median | unoptimised ratio median | nonzero-digit ratio median | n |
|---|---|---|---|---|---|---|---|---|
| 2 | 4.77e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 3 | 1.31e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 4 | 3.83e-03 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 5 | 1.13e-03 | 1.051 | 1.055 | 1.057 | 1.060 | 1.034 | 1.176 | 6 |
| 6 | 3.29e-04 | 1.063 | 1.067 | 1.075 | 1.016 | 1.081 | 1.176 | 6 |
| 7 | 8.97e-05 | 1.069 | 1.076 | 1.078 | 0.980 | 1.120 | 1.178 | 6 |
| 8 | 2.41e-05 | 1.070 | 1.071 | 1.073 | 0.943 | 1.143 | 1.171 | 6 |

**block 2x2**

| binary K | MSE (256, seed 0) | ratio min | ratio median | ratio max | density ratio median | unoptimised ratio median | nonzero-digit ratio median | n |
|---|---|---|---|---|---|---|---|---|
| 2 | 4.77e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 3 | 1.31e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 4 | 3.83e-03 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 5 | 1.13e-03 | 1.065 | 1.071 | 1.077 | 1.075 | 1.074 | 1.223 | 6 |
| 6 | 3.29e-04 | 1.070 | 1.074 | 1.083 | 1.023 | 1.095 | 1.224 | 6 |
| 7 | 8.97e-05 | 1.070 | 1.075 | 1.076 | 0.979 | 1.109 | 1.219 | 6 |
| 8 | 2.41e-05 | 1.066 | 1.069 | 1.069 | 0.941 | 1.113 | 1.208 | 6 |

**block 4x4**

| binary K | MSE (256, seed 0) | ratio min | ratio median | ratio max | density ratio median | unoptimised ratio median | nonzero-digit ratio median | n |
|---|---|---|---|---|---|---|---|---|
| 2 | 4.77e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 3 | 1.31e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 4 | 3.83e-03 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 5 | 1.13e-03 | 1.035 | 1.037 | 1.043 | 1.041 | 1.008 | 1.152 | 6 |
| 6 | 3.29e-04 | 1.083 | 1.088 | 1.092 | 1.035 | 1.064 | 1.130 | 6 |
| 7 | 8.97e-05 | 1.092 | 1.099 | 1.100 | 1.001 | 1.118 | 1.130 | 6 |
| 8 | 2.41e-05 | 1.091 | 1.093 | 1.099 | 0.962 | 1.158 | 1.128 | 6 |

### laplace weights

**block 1x4**

| binary K | MSE (256, seed 0) | ratio min | ratio median | ratio max | density ratio median | unoptimised ratio median | nonzero-digit ratio median | n |
|---|---|---|---|---|---|---|---|---|
| 2 | 8.69e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 3 | 2.99e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 4 | 1.03e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 5 | 3.41e-03 | 1.097 | 1.103 | 1.122 | 1.102 | 1.109 | 1.267 | 6 |
| 6 | 1.06e-03 | 1.090 | 1.106 | 1.114 | 1.049 | 1.110 | 1.251 | 6 |
| 7 | 2.99e-04 | 1.091 | 1.098 | 1.110 | 0.998 | 1.113 | 1.240 | 6 |
| 8 | 7.81e-05 | 1.083 | 1.085 | 1.088 | 0.955 | 1.110 | 1.224 | 6 |

**block 1x8**

| binary K | MSE (256, seed 0) | ratio min | ratio median | ratio max | density ratio median | unoptimised ratio median | nonzero-digit ratio median | n |
|---|---|---|---|---|---|---|---|---|
| 2 | 8.69e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 3 | 2.99e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 4 | 1.03e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 5 | 3.41e-03 | 1.064 | 1.072 | 1.090 | 1.070 | 1.079 | 1.242 | 6 |
| 6 | 1.06e-03 | 1.078 | 1.093 | 1.100 | 1.036 | 1.099 | 1.220 | 6 |
| 7 | 2.99e-04 | 1.087 | 1.094 | 1.108 | 0.994 | 1.118 | 1.205 | 6 |
| 8 | 7.81e-05 | 1.084 | 1.086 | 1.091 | 0.955 | 1.133 | 1.191 | 6 |

**block 2x2**

| binary K | MSE (256, seed 0) | ratio min | ratio median | ratio max | density ratio median | unoptimised ratio median | nonzero-digit ratio median | n |
|---|---|---|---|---|---|---|---|---|
| 2 | 8.69e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 3 | 2.99e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 4 | 1.03e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 5 | 3.41e-03 | 1.096 | 1.104 | 1.122 | 1.103 | 1.108 | 1.266 | 6 |
| 6 | 1.06e-03 | 1.090 | 1.105 | 1.113 | 1.048 | 1.110 | 1.252 | 6 |
| 7 | 2.99e-04 | 1.090 | 1.098 | 1.110 | 0.998 | 1.111 | 1.240 | 6 |
| 8 | 7.81e-05 | 1.083 | 1.085 | 1.088 | 0.955 | 1.111 | 1.224 | 6 |

**block 4x4**

| binary K | MSE (256, seed 0) | ratio min | ratio median | ratio max | density ratio median | unoptimised ratio median | nonzero-digit ratio median | n |
|---|---|---|---|---|---|---|---|---|
| 2 | 8.69e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 3 | 2.99e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 4 | 1.03e-02 | - | - | - | - | - | - | 0 (outside phi MSE range) |
| 5 | 3.41e-03 | 1.058 | 1.064 | 1.077 | 1.062 | 1.064 | 1.219 | 6 |
| 6 | 1.06e-03 | 1.084 | 1.099 | 1.106 | 1.043 | 1.109 | 1.194 | 6 |
| 7 | 2.99e-04 | 1.108 | 1.115 | 1.124 | 1.013 | 1.142 | 1.167 | 6 |
| 8 | 7.81e-05 | 1.108 | 1.111 | 1.113 | 0.977 | 1.168 | 1.149 | 6 |

### Verdict

- block 1x4 (Gaussian, all in-range binary K, both sizes): worst ratio 1.082, best 1.066; worst per seed seed 0: 1.076, seed 1: 1.082, seed 2: 1.075 -> fails the < 0.9 test
- block 4x4 (Gaussian, all in-range binary K, both sizes): worst ratio 1.100, best 1.035; worst per seed seed 0: 1.100, seed 1: 1.099, seed 2: 1.099 -> fails the < 0.9 test

# NO-GO

At matched MSE, phi does not get its active block-ops below 0.9x binary consistently for 1x4 or 4x4 even though both get the same block optimiser; see the density ratios above (needs < 0.69 to tie).
