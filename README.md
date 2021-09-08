- 👋 Hi, I’m @Srilathavunnam
- 👀 I’m interested in playing cricket
- 🌱 I’m currently learning webapps
- 💞️ I’m looking to collaborate on google
- 📫 How to reach me Instagram,snapchat <https://www.instagram.com/srilatha_0728/>

<!---
Srilathavunnam/Srilathavunnam is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# SRILATHA VUNNAM
###### New York City


>New York, often called New York City to distinguish it from New York State, or **NYC for short**, is the most populous city in the United States. With a 2020 population of 8,804,190 distributed over 300.46 square miles (778.2 km2),[2] New York City is also the most densely populated major city in the United States. Located at the southern tip of the State of New York, the city is the center of the New York metropolitan area, **the largest metropolitan area in the world by urban area**.[10] With over 20 million people in its metropolitan statistical area and approximately 23 million in its combined statistical area, it is one of the world's most populous megacities. New York City has been described as the cultural, financial, and media capital of the world, significantly influencing commerce,[11] entertainment, research, technology, education, politics, tourism, art, fashion, and sports, and is the most photographed city in the world.[12] Home to the headquarters of the United Nations,[13] New York is an important center for international diplomacy,[14][15] and has sometimes been called the capital of the world.[16][17]
***
# Heading for access to reach order list and unorder list
1. Maryville 
2. New York City
   1. Alice Austen House
   2. terminal
3. utah
 * Road trips
 * Backpacking
   * Cycling
   * Fishing
   * Camping
**[LinktoAboutme.md](AboutMe.md)**

# heading about creating a table food/drinks

Introduction:
 The following is to create a table with at least 4food/drinksthat you would recommend someone try.Include a short paragraph that introduces the table.

|Mandatory|fav1              |fav2            |fav3               |fav4           |
|:------: | :--------:       | :-------:      | :-------:         | :-------:     |
|Food     |mutton tikka      |Idly            |Ice creame         |drinks         |
|Location |hyderbad          |guntur          |vijaywada          |thumps         |
|Type     |Double Spicy      |with ghee       |Large              |Large          |
|Amout    |40-50             |40-30           |30-20              |20-10          |

----
# quotes section
>A “It’s not enough to be **friendly**. You have to be a friend.” .
>Author:*R.J. Palacio, Wonder* <br>
>“‘You have been**my friend,’ replied Charlotte**. ‘That in itself is a tremendous thing.’” 
>Author:*E.B. White, Charlotte’s Web*

----
# Create a new section about code Fencing
>Combinatorics is an area of mathematics primarily concerned with counting, both as a means and an end in obtaining results, and certain properties of finite structures. It is closely related to many other areas of mathematics and has many applications ranging from logic to statistical physics, from evolutionary biology to computer science, etc.qick link to source code<https://en.wikipedia.org/wiki/Combinatorics>
```
int solve (int n, int r) {
    vector<int> p;
    for (int i=2; i*i<=n; ++i)
        if (n % i == 0) {
            p.push_back (i);
            while (n % i == 0)
                n /= i;
        }
    if (n > 1)
        p.push_back (n);

    int sum = 0;
    for (int msk=1; msk<(1<<p.size()); ++msk) {
        int mult = 1,
            bits = 0;
        for (int i=0; i<(int)p.size(); ++i)
            if (msk & (1<<i)) {
                ++bits;
                mult *= p[i];
            }

        int cur = r / mult;
        if (bits % 2 == 1)
            sum += cur;
        else
            sum -= cur;
    }

    return r - sum;
}
```
quick link to source code<https://cp-algorithms.com/combinatorics/inclusion-exclusion.html>

