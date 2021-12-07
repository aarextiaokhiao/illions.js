# illions.js
A library for generating illions and standard notation with really huge numbers.
[Made by Aarex Tiaokhiao, 2021.](https://aarextiaokhiao.github.io/googology/)

Feel free to use it at: https://github.com/aarextiaokhiao/illions.js/blob/main/illions.js
Or if you want to wish for a simpler program with less variety, check out [the lite version]( https://github.com/aarextiaokhiao/illions.js/blob/main/illions.js).

Check out the changelog at [another document](changelog.md).

# [DECIMAL LIBRARY IS REQUIRED]
You can use one of either libraries:
- **logarithmica_numerus_lite.js**: https://github.com/aarextiaokhiao/magna_numerus.js/blob/master/logarithmica_numerus_lite.js
- **break_eternity.js**: https://github.com/Patashu/break_eternity.js/blob/master/break_eternity.js

Although break_eternity.js doesn't produce perfect powers of tens from ``Decimal.pow(10, x)``, this library also includes a fix to these exponents.

# Limits and Features
Currently, this library generates names up to a killillion, which is equal to \*10^(3*10^3*10^3000+3)\*.

The lite version goes up to icosillion (\*10^(3*10^3*10^3000+3)\*), but the full version contains more features like Tamara's illions, myrillions, and more.

It is likely that I will stop at Redillion, which is baseline Tier 7. Although, there would be my fanmade illions after it if this doesn't happen.

# Examples
```
illion(20) -> vigintillion
standard(77) -> SSt
name("3.21e3002") -> 321.00 novemnonagintanongentillion
format("1.03e5431") -> 10.30 Mi-NOe
```

# Sources
- Tier 1 - 4:
-- https://sites.google.com/site/largenumbers/home/2-4/8
-- https://sites.google.com/site/pointlesslargenumberstuff/home/1/bowersillions
- Tier 4 - 6: https://integralview.wordpress.com/2020/10/01/extended-tier-4-to-6-illions/
- Fonster's 2M Prefixes (Tier 5): https://sites.google.com/site/pointlesslargenumberstuff/home/l/pgln2/2msiprefixes
- Connections: https://docs.google.com/document/d/1dhCjmN9_qOyydKY6a_rzbCfNg8yIGslEPVfA9iz60Ig/edit?usp=sharing
- Tamara's Illions: https://tamaramacadam.me/maths/largenumbers/illions.html