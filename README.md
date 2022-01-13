<h2>SAPT calculation</h2>
<ul>
  <li>zn.com</li>
  <p>Gaussian optimization input file</p>
  <li>zn.log</li>
  <p>Gaussian optimization output file</p>
  <li>zn_sapt.in</li>
  <p>PSI4 SAPT analysis input file</p>
  <li>zn_sapt.log</li>
  <p>PSI4 SAPT analysis output file</p>
</ul>
<h2>SAPT Results</h2>
<pre line="1" lang=python>
    SAPT Results 
  --------------------------------------------------------------------------------------------------------
    Electrostatics               -162.47876877 [mEh]    -101.95696669 [kcal/mol]    -426.58794863 [kJ/mol]
      Elst10,r                   -162.47876877 [mEh]    -101.95696669 [kcal/mol]    -426.58794863 [kJ/mol]

    Exchange                       49.97442011 [mEh]      31.35942207 [kcal/mol]     131.20782193 [kJ/mol]
      Exch10                       49.97442011 [mEh]      31.35942207 [kcal/mol]     131.20782193 [kJ/mol]
      Exch10(S^2)                  49.66249445 [mEh]      31.16368576 [kcal/mol]     130.38886123 [kJ/mol]

    Induction                    -192.88830752 [mEh]    -121.03924035 [kcal/mol]    -506.42818163 [kJ/mol]
      Ind20,r                    -399.98642615 [mEh]    -250.99527179 [kcal/mol]   -1050.16421718 [kJ/mol]
      Exch-Ind20,r                218.85604841 [mEh]     137.33424377 [kcal/mol]     574.60647595 [kJ/mol]
      delta HF,r (2)              -11.75792978 [mEh]      -7.37821233 [kcal/mol]     -30.87044039 [kJ/mol]

    Dispersion                     -8.97017911 [mEh]      -5.62887237 [kcal/mol]     -23.55120201 [kJ/mol]
      Disp20                      -10.56548697 [mEh]      -6.62994317 [kcal/mol]     -27.73968222 [kJ/mol]
      Exch-Disp20                   1.59530786 [mEh]       1.00107080 [kcal/mol]       4.18848021 [kJ/mol]
      Disp20 (SS)                  -5.28274349 [mEh]      -3.31497158 [kcal/mol]     -13.86984111 [kJ/mol]
      Disp20 (OS)                  -5.28274349 [mEh]      -3.31497158 [kcal/mol]     -13.86984111 [kJ/mol]
      Exch-Disp20 (SS)              0.63749845 [mEh]       0.40003632 [kcal/mol]       1.67375195 [kJ/mol]
      Exch-Disp20 (OS)              0.95780941 [mEh]       0.60103448 [kcal/mol]       2.51472826 [kJ/mol]

  Total HF                       -305.39265618 [mEh]    -191.63678497 [kcal/mol]    -801.80830833 [kJ/mol]
  Total SAPT0                    -314.36283529 [mEh]    -197.26565735 [kcal/mol]    -825.35951034 [kJ/mol]

  Special recipe for scaled SAPT0 (see Manual):
    Electrostatics sSAPT0        -162.47876877 [mEh]    -101.95696669 [kcal/mol]    -426.58794863 [kJ/mol]
    Exchange sSAPT0                49.97442011 [mEh]      31.35942207 [kcal/mol]     131.20782193 [kJ/mol]
    Induction sSAPT0             -188.73850637 [mEh]    -118.43520081 [kcal/mol]    -495.53288021 [kJ/mol]
    Dispersion sSAPT0              -8.93992996 [mEh]      -5.60989074 [kcal/mol]     -23.47178287 [kJ/mol]
  Total sSAPT0                   -310.18278499 [mEh]    -194.64263618 [kcal/mol]    -814.38478978 [kJ/mol]
</pre>
<h2>OEChem Interaction</h2>
<img src="https://github.com/gkxiao/3max/blob/main/3max.png"  alt="PDB 3MAX">
<iframe style="border:none;" src="https://github.com/gkxiao/3max/blob/main/3max-llx-zn.html" name="ircframe" marginwidth="0" marginheight="0" scrolling="yes" seamless="seamless" width="100%" height="500">
<br />
Your browser does not support iframes. 
<a target="_blank" href="https://github.com/gkxiao/3max/blob/main/3max-llx-zn.html">View the code here</a>
<br/>
</iframe>
