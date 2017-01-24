# html-imports-benchmark

Performance tests for html-imports v0 vs v1 implementations.

```bash
$ npm install -g polymer-cli
$ bower install
$ polymer serve
```

Then open `index.html` and run the tests.

## Results

Averages of 10 runs on different browsers.

Browser   | v0      | v1      | v1 (es6) | v0-v1 (ms) | v0-v1 (%) | v1-v1 (es6) (ms) | v1-v1 (es6) (%)
--------- | ------- | ------- | -------- | ---------- | --------- | ---------------- | ---------------
Chrome    | 405.34  | 374.05  | 345.98   | 31.30      | 7.72      | 28.07            | 7.50
Canary    | 323.14  | 277.99  | 271.88   | 45.15      | 13.97     | 6.11             | 2.20
Firefox   | 3019.35 | 1216.17 | 1307.22  | 1803.18    | 59.72     | -91.05           | -7.49
Safari 10 | 484.36  | 483.37  | 471.92   | 0.98       | 0.20      | 11.45            | 2.37
Safari TP | 333.56  | 360.71  | 346.28   | -27.15     | -8.14     | 14.43            | 4.00
MS Edge   | 2903.92 | 1973.65 | 1966.86  | 930.27     | 32.03     | 6.79             | 0.34
MS IE11   | 3237.18 | 3773.37 | 3794.93  | -536.19    | -16.56    | -                | -
