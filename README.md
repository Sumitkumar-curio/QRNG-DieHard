# QRNG-DieHard
For Binary Data file Outut 2. Quantum Random number generator.

sudo apt-get install dieharder
sudo apt-get install libdieharder-dev
dpkg -l | grep dieharder
dpkg -l | grep gsl
man dieharder
dieharder -v
cd Downloads
binary_output.txt
dieharder -a -f binary_output2.txt

#=============================================================================#
#            dieharder version 3.31.1 Copyright 2003 Robert G. Brown          #
#=============================================================================#
   rng_name    |           filename             |rands/second|
        mt19937|              binary_output2.txt|  1.70e+07  |
Here's the data in a tabular format that you can use for your README or documentation:

| Test Name                      | ntup | tsamples | psamples | p-value      | Assessment |
|--------------------------------|------|----------|----------|--------------|------------|
| diehard_birthdays              | 0    | 100      | 100      | 0.91088416   | PASSED     |
| diehard_operm5                 | 0    | 1000000  | 100      | 0.34971292   | PASSED     |
| diehard_rank_32x32             | 0    | 40000    | 100       | 0.67227970    | PASSED     |
| diehard_rank_6x8               | 0    | 100000   | 100       | 0.76219697    | PASSED     |
| diehard_bitstream              | 0    | 2097152  | 100      | 0.27336921   | PASSED     |
| diehard_opso                   | 0    | 2097152  | 100      | 0.48417279   | PASSED     |
| diehard_oqso                   | 0    | 2097152  | 100      | 0.72537769   | PASSED     |
| diehard_dna                    | 0    | 2097152  | 100      | 0.28605357   | PASSED     |
| diehard_count_1s_str           | 0    | 256000   | 100      | 0.72009025   | PASSED     |
| diehard_count_1s_byt           | 0    | 256000   | 100      | 0.11602562   | PASSED     |
| diehard_parking_lot           | 0    | 12000    | 100      | 0.97946883   | PASSED     |
| diehard_2dsphere              | 2    | 8000     | 100      | 0.56820811   | PASSED     |
| diehard_3dsphere              | 3    | 4000     | 100      | 0.30134087   | PASSED     |
| diehard_squeeze               | 0    | 100000   | 100      | 0.11489486   | PASSED     |
| diehard_sums                  | 0    | 100      | 100      | 0.22905076   | PASSED     |
| diehard_runs                  | 0    | 100000   | 100      | 0.87066632   | PASSED     |
| diehard_runs                  | 0    | 100000   | 100      | 0.01880172   | PASSED     |
| diehard_craps                 | 0    | 200000   | 100      | 0.35548734   | PASSED     |
| diehard_craps                 | 0    | 200000   | 100      | 0.23137819   | PASSED     |
| marsaglia_tsang_gcd           | 0    | 10000000 | 100      | 0.98732141   | PASSED     |
| marsaglia_tsang_gcd           | 0    | 10000000 | 100      | 0.98971297   | PASSED     |
| sts_monobit                   | 1    | 100000   | 100      | 0.02686061   | PASSED     |
| sts_runs                      | 2    | 100000   | 100      | 0.33630387   | PASSED     |
| sts_serial                    | 1    | 100000   | 100      | 0.85246403   | PASSED     |
| sts_serial                    | 2    | 100000   | 100      | 0.27591560   | PASSED     |
| sts_serial                    | 3    | 100000   | 100      | 0.02448923   | PASSED     |
| sts_serial                    | 3    | 100000   | 100      | 0.04161327   | PASSED     |
| sts_serial                    | 4    | 100000   | 100      | 0.10261999   | PASSED     |
| sts_serial                    | 4    | 100000   | 100      | 0.55113060   | PASSED     |
| sts_serial                    | 5    | 100000   | 100      | 0.46836317   | PASSED     |
| sts_serial                    | 5    | 100000   | 100      | 0.61736399   | PASSED     |
| sts_serial                    | 6    | 100000   | 100      | 0.11718685   | PASSED     |
| sts_serial                    | 6    | 100000   | 100      | 0.33910613   | PASSED     |
| sts_serial                    | 7    | 100000   | 100      | 0.26591895   | PASSED     |
| sts_serial                    | 7    | 100000   | 100      | 0.69935910   | PASSED     |
| sts_serial                    | 8    | 100000   | 100      | 0.97529162   | PASSED     |
| sts_serial                    | 8    | 100000   | 100      | 0.04777839   | PASSED     |
| sts_serial                    | 9    | 100000   | 100      | 0.38104705   | PASSED     |
| sts_serial                    | 9    | 100000   | 100      | 0.04457882   | PASSED     |
| sts_serial                    | 10   | 100000   | 100      | 0.98566771   | PASSED     |
| sts_serial                    | 10   | 100000   | 100      | 0.98882750   | PASSED     |
| sts_serial                    | 11   | 100000   | 100      | 0.12885066   | PASSED     |
| sts_serial                    | 11   | 100000   | 100      | 0.04245456   | PASSED     |
| sts_serial                    | 12   | 100000   | 100      | 0.00495070   | WEAK       |
| sts_serial                    | 12   | 100000   | 100      | 0.02399071   | PASSED     |
| sts_serial                    | 13   | 100000   | 100      | 0.08055456   | PASSED     |
| sts_serial                    | 13   | 100000   | 100      | 0.80370804   | PASSED     |
| sts_serial                    | 14   | 100000   | 100      | 0.76197005   | PASSED     |
| sts_serial                    | 14   | 100000   | 100      | 0.91972517   | PASSED     |
| sts_serial                    | 15   | 100000   | 100      | 0.05400461   | PASSED     |
| sts_serial                    | 15   | 100000   | 100      | 0.27123778   | PASSED     |
| sts_serial                    | 16   | 100000   | 100      | 0.56574484   | PASSED     |
| sts_serial                    | 16   | 100000   | 100      | 0.71146249   | PASSED     |
| rgb_bitdist                   | 1    | 100000   | 100      | 0.37541986   | PASSED     |
| rgb_bitdist                   | 2    | 100000   | 100      | 0.96796363   | PASSED     |
| rgb_bitdist                   | 3    | 100000   | 100      | 0.23805959   | PASSED     |
| rgb_bitdist                   | 4    | 100000   | 100      | 0.87484411   | PASSED     |
| rgb_bitdist                   | 5    | 100000   | 100      | 0.99435408   | PASSED     |
| rgb_bitdist                   | 6    | 100000   | 100      | 0.48276982   | PASSED     |
| rgb_bitdist                   | 7    | 100000   | 100      | 0.92917224   | PASSED     |
| rgb_bitdist                   | 8    | 100000   | 100      | 0.89168527   | PASSED     |
| rgb_bitdist                   | 9    | 100000   | 100      | 0.96904599   | PASSED     |
| rgb_bitdist                   | 10   | 100000   | 100      | 0.11358462   | PASSED     |
| rgb_bitdist                   | 11   | 100000   | 100      | 0.20348258   | PASSED     |
| rgb_bitdist                   | 12   | 100000   | 100      | 0.57409853   | PASSED     |
| rgb_minimum_distance          | 2    | 10000    | 1000     | 0.36250261   | PASSED     |
| rgb_minimum_distance          | 3    | 10000    | 1000     | 0.53233276   | PASSED     |
| rgb_minimum_distance          | 4    | 10000    | 1000     | 0.10784369   | PASSED     |
| rgb_minimum_distance          | 5    | 10000    | 1000     | 0.16848636   | PASSED     |
| rgb_permutations              | 2    | 100000   | 100      | 0.93885971   | PASSED     |
| rgb_permutations              | 3    | 100000   | 100      | 0.09980266   | PASSED     |
| rgb_permutations              | 4    | 100000   | 100      | 0.96659490   | PASSED     |
| rgb_permutations              | 5    | 100000   | 100      | 0.78098543   | PASSED     |
| rgb_lagged_sum                | 0    | 1000000  | 100      | 0.57730198   | PASSED     |
| rgb_lagged_sum                | 1    | 1000000  | 100      | 0.85180213   | PASSED     |
| rgb_lagged_sum                | 2    | 1000000  | 100      | 0.43380480   | PASSED     |
| rgb_lagged_sum                | 3    | 1000000  | 100      | 0.19218276   | PASSED     |
| rgb_lagged_sum                | 4    | 1000000  | 100      | 0.53990973   | PASSED     |
| rgb_lagged_sum                | 5    | 1000000  | 100      | 0.87843486   | PASSED     |
| rgb_lagged_sum                | 6    | 1000000  | 100      | 0.21913205   | PASSED     |
| rgb_lagged_sum                | 7    | 1000000  | 100      | 0.06027132   | PASSED     |
| rgb_lagged_sum                | 8    | 1000000  | 100      | 0.71840015   | PASSED     |
| rgb_lagged_sum                | 9    | 1000000  | 100      | 0.96914031   | PASSED     |
| rgb_lagged_sum                | 10   | 1000000  | 100      | 0.67929659   | PASSED     |
| rgb_lagged_sum                | 11   | 1000000  | 100      | 0.67788082   | PASSED     |
| rgb_lagged_sum                | 12   | 1000000  | 100      | 0.59333396   | PASSED     |
| rgb_lagged_sum                | 13   | 1000000  | 100      | 0.95379794   | PASSED     |
| rgb_lagged_sum                | 14   | 1000000  | 100      | 0.08420541   | PASSED     |
| rgb_lagged_sum                | 15   | 1000000  | 100      | 0.97806831   | PASSED     |
| rgb_lagged_sum                | 16   | 1000000  | 100      | 0.42151882   | PASSED     |
| rgb_lagged_sum                | 17   | 1000000  | 100      | 0.65285144   | PASSED     |
| rgb_lagged_sum                | 18   | 1000000  | 100      | 0.56537774   | PASSED     |
| rgb_lagged_sum                | 19   | 1000000  | 100      | 0.76658545   | PASSED     |
| rgb_lagged_sum                | 20   | 1000000  | 100      | 0.91831718   | PASSED     |
| rgb_lagged_sum                | 21   | 1000000  | 100      | 0.96754603   | PASSED     |
| rgb_lagged_sum                | 22   | 1000000  | 100      | 0.99947593   | WEAK       |
| rgb_lagged_sum                | 23   | 1000000  | 100      | 0.99946583   | WEAK       |
| rgb_lagged_sum                | 24   | 1000000  | 100      | 0.54156150   | PASSED     |
| rgb_lagged_sum                | 25   | 1000000  | 100      | 0.54959154   | PASSED     |
| rgb_lagged_sum                | 26   | 1000000  | 100      | 0.13494025   | PASSED     |
| rgb_lagged_sum                | 27   | 1000000  | 100      | 0.95548421   | PASSED     |
| rgb_lagged_sum                | 28   | 1000000  | 100      | 0.80959370   | PASSED     |
| rgb_lagged_sum                | 29   | 1000000  | 100      | 0.09321913   | PASSED     |
| rgb_lagged_sum                | 30   | 1000000  | 100      | 0.84569819   | PASSED     |
| rgb_lagged_sum                | 31   | 1000000  | 100      | 0.56779178   | PASSED     |
| rgb_lagged_sum                | 32   | 1000000  | 100      | 0.03361580   | PASSED     |
| rgb_kstest_test               | 0    | 10000    | 1000     | 0.22746354   | PASSED     |
| dab_bytedistrib               | 0    | 51200000 | 1        | 0.95774898   | PASSED     |
| dab_dct                       | 256  | 50000    | 1        | 0.52843799   | PASSED     |
| dab_filltree                  | 32   | 15000000 | 1        | 0.24305124   | PASSED     |
| dab_filltree                  | 32   | 15000000 | 1        | 0.71077585   | PASSED     |
| dab_filltree2                 | 0    | 5000000  | 1        | 0.39573147   | PASSED     |
| dab_filltree2                 | 1    | 5000000  | 1        | 0.22975306   | PASSED     |
| dab_monobit2                 | 12   | 65000000 | 1         | 0.53374292   | PASSED     |


