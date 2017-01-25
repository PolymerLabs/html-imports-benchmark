# html-imports-benchmark

Performance tests for html-imports v0 vs v1 implementations.

```bash
$ npm install -g polymer-cli
$ bower install
$ polymer serve
```

Then open `index.html` and run the tests.

## Results

Averages of 30 runs on different browsers.

Browser      | v0      | v1      | v1 (es6) | v0-v1 (ms) | v0-v1 (%) | v1-v1 (es6) (ms) | v1-v1 (es6) (%)
------------ | ------- | ------- | -------- | ---------- | --------- | ---------------- | ---------------
Chrome 55    | 284.71  | 272.97  | 267.95   | 11.74      | 4.12      | 5.02             | 1.84
Canary 58    | 252.97  | 238.60  | 227.68   | 14.38      | 5.68      | 10.92            | 4.58
Firefox 51   | 1026.59 | 742.14  | 690.93   | 284.44     | 27.71     | 51.22            | 6.90
Safari 10    | 311.11  | 245.68  | 243.22   | 65.43      | 21.03     | 2.46             | 1.00
Safari TP    | 316.77  | 257.15  | 256.66   | 59.62      | 18.82     | 0.49             | 0.19
Win10 MSEdge | 1208.06 | 954.23  | 990.17   | 253.83     | 21.01     | -35.94           | -3.77
Win8.1 IE11  | 1218.34 | 1191.95 | -        | 26.39      | 2.17      | -                | -
