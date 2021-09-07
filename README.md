# assignment2_Punaati
# Chaitanya Punaati #
###### Kodaikanal ######
**Kodaikanal is one of the best hill station in south India.** It’s set in an area of granite cliffs, forested valleys, lakes, waterfalls and grassy hills. At 2,000 meters above sea level, the town centers around man-made, star-shaped Kodaikanal Lake, bordered by evergreen forest. **The beautiful lakes and pleasant whether gives positive vibes.** This is the reason this place and it is best place for holiday visit.

<hr/>

# Ordered List #

1. Go to Kansas Airport from Maryville 
2. Board India flight and land at Chennai International Airport located in Chennai city, Tamilnadu state.
    1. Go to Chennai Egmore railway station from chennai international airport.
    2. Board the train which is going to Madhurai railway station and get down there.
    3. Take any public transport like car, jeep, bus etc., to go to Kodaikanal.

* Leather jacket
* Gloves
* Sox
* Camera
* Food
    * Water bottles
    * Snacks

<hr/>

[Link to Aboutme.md file](https://github.com/ChaitanyaPunaati/assignment2_Punaati/blob/main/AboutMe.md)

<hr/>

# Table Section #

I have mentioned few delicious food/drinks below that i would really recommend you to try.

| Food/Drink | Location | Amount |
| --- | --- | --- |
| Burger | Chick-fil-A | $4 |
| Pizza | Dominos | $10 |
| Whole weat | SUBWAY | $6 |
| Pepsi | Campus Dining | $2 |

<hr/>

# Pithy Quotes #

> You will face many defeats in life, but never let yourself be defeated. -  _MAYA ANGELOU_
> 
> The happiness of your life depends on the quality of your thoughts. -  _MARCUS AURELIUS_
>

<hr/>

# Code Fencing #

> In geometry, the area is defined as the region occupied inside the boundary of a two-dimensional figure. Therefore, the area of a polygon is the total space or region bound by the sides of a polygon.
>
> The standard units for the measurement of the area are square meters (m2).

[Link to Algorithm description](https://www.storyofmathematics.com/area-of-polygon)

```
double area(const vector<point>& fig) {
    double res = 0;
    for (unsigned i = 0; i < fig.size(); i++) {
        point p = i ? fig[i - 1] : fig.back();
        point q = fig[i];
        res += (p.x - q.x) * (p.y + q.y);
    }
    return fabs(res) / 2;
}
```

[Link to the code source](https://cp-algorithms.com/geometry/area-of-simple-polygon.html#toc-tgt-1)