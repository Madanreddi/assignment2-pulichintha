# assignment2-pulichintha
public repository

# madan mohan reddy pulichintha

#### charminar

charminar is one of the most **famous building** in india.it was built by muhammad quli qutb shahi to celebrate the end of **deadly plague**.

---

# Directions fortravelling from Maryville to charminar
1. Book a cab from Maryville to kansas airport
2. Finish the security check.
   1. Finish the security check.
   2. Board your flight.
   3. waiting for the connecting flight in chicago.
3. O Hare International airport to rajiv gandhi international airport
   1. complete the check out process in hyderabad
   2. Book a bus ticket to charminar
4. Book a cab from hyderabad to charminar

* clothes
* books
* camera
* food
  * rice
  * powders

  [aboutme](AboutMe.md)

  # Table creation
  The above table recommends some of my best food and drinks I exprienced till now

  |    Food/drink      |    location          |  price  |
  |    -----           |    -----             |  -----  |
  |    chicken pizza   |  Dominos             |  $9     |
  |    veg burger      |  pizza hut           |  $4     |
  |    veg sandwich    |  Tacobell            |  $12    |
  |    chicken bbq     |  Nation              |  $13    |



# Quotes by greatest people
     > "THe greatest glory in living lies not in neverv falling, but in rising every time we fall". ***Nelson Mandela***
     > "If life were predictable it would cease to be life, and be without flavour". ***Eleanor Roosevelt***

# Algorithm on Combinatorics    

  "Combinatorics is a range of linked studies which have something in common and yet diverge widely in their objectives, their methods, and the degree of coherence they have attained."[3] One way to define combinatorics is, perhaps, to describe its subdivisions with their problems and techniques.  

  Source link for definition <https://en.wikipedia.org/wiki/Combinatorics> 

```

int C(int n, int k) {
    int res = 1;
    for (int i = n - k + 1; i <= n; ++i)
        res *= i;
    for (int i = 2; i <= k; ++i)
        res /= i;
    return res;
}

```
Source link for code <https://cp-algorithms.com/combinatorics/binomial-coefficients.html>