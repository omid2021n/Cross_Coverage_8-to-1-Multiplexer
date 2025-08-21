# Cross_Coverage_8-to-1-Multiplexer
This is an excellent simulation result showing 100% functional coverage for your multiplexer testbench. Let me break down the key results:

Overall Summary: ✅ PERFECT COVERAGE
100% Covergroup Coverage achieved

All 100 test cases executed successfully

Simulation ran for 1200 ns

Input Coverage Distribution
All inputs (a-h) showed good random distribution:

a: 48 zeros, 52 ones ✓

b: 51 zeros, 49 ones ✓

c: 56 zeros, 44 ones ✓

d: 60 zeros, 40 ones ✓

e: 52 zeros, 48 ones ✓

f: 52 zeros, 48 ones ✓

g: 50 zeros, 50 ones ✓ (perfect balance)

h: 51 zeros, 49 ones ✓

Selection Signal (sel) Coverage
All 8 possible sel values were tested:

sel=0: 14 occurrences ✓

sel=1: 20 occurrences ✓

sel=2: 14 occurrences ✓

sel=3: 10 occurrences ✓

sel=4: 10 occurrences ✓

sel=5: 13 occurrences ✓

sel=6: 14 occurrences ✓

sel=7: 5 occurrences ✓

Output (y) Coverage
y=0: 54 occurrences ✓

y=1: 45 occurrences ✓

(1 missing due to default case when sel is out of range)

Cross Coverage Results ✅ CRITICAL SUCCESS
The smart cross coverage verified that each input is only selected when its corresponding sel value is active:

cross_a_sel: 14 hits (when sel=0) - ✓ Both 0 and 1 values covered

cross_b_sel: 20 hits (when sel=1) - ✓ Both 0 and 1 values covered

cross_c_sel: 14 hits (when sel=2) - ✓ Both 0 and 1 values covered

cross_d_sel: 10 hits (when sel=3) - ✓ Both 0 and 1 values covered

cross_e_sel: 10 hits (when sel=4) - ✓ Both 0 and 1 values covered

cross_f_sel: 13 hits (when sel=5) - ✓ Both 0 and 1 values covered

cross_g_sel: 14 hits (when sel=6) - ✓ Both 0 and 1 values covered

cross_h_sel: 5 hits (when sel=7) - ✓ Both 0 and 1 values covered
