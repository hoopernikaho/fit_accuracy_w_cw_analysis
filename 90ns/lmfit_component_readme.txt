[[Model]]
    (Model(one_pulse, prefix='one_') + Model(one_pulse, prefix='two_'))
[[Variables]]
    one_x_offset:      4.0667e-07 (init= 3.711404e-07)
    two_x_offset:      4.0644e-07 (init= 8.731403e-07)
    sum_amplitudes:    1.99256005 (init= 1.955794)
    diff_amplitudes:   0.16158414 (init= 0)
    one_amplitude:     1.07707209  == '(sum_amplitudes + diff_amplitudes)/2'
    two_amplitude:     0.91548795  == '(sum_amplitudes - diff_amplitudes)/2'
