# assignment2-barugu
Second Assignment about Markdown.
# Barugu Manoj Kumar
## Hyderabad

**Hyderabad** is the capital and largest city of the Indian state of **Telangana** and the de jure capital of Andhra Pradesh. It occupies 650 km2 (250 sq mi) on the Deccan Plateau along the banks of the Musi River, in the northern part of South India.

***

### Paradise Restaurant

Rajiv Gandhi International Airport is an international airport that serves Hyderabad, the capital of the Indian state of Telangana.

1. The distance between Hyderabad Airport to paradise biryani Hyderabad is 8 Km by road. 
2. You can also find the distance from Hyderabad Airport to paradise biryani Hyderabad using other travel options like bus, subway, tram, train and rail.
3. Apart from the trip distance, refer Directions from Hyderabad Airport to paradise biryani Hyderabad for road driving directions.

- Hyderabad biryani
- Butter chicken
- Mutton kababs
- Mutton Biryani

[link to about me](Aboutme.md)

***
### Sports and activities

Sports are defined as physical or mental exertion by individuals and are committed to maintaining physical or mental fitness. There are many types of exercise that can be practiced as a healthy habit, such as walking, riding, Swimming, or athletics, and these sports have many benefits on the human body and mind.

| Name  | Location  |  Price |
|---|---|---|
|  Cricket |  Hyderabad |  $50 | 
|  Football | Missouri  |  $30 |
|  Basketball | Kansas  |  $20 |
|  Badminton | Maryville | $10 |

***
### Favourite Quotes

> Dream without fear Love without limits - *Manoj Barugu*
>
> Trust In God - *King David*

***

### Algorithm

> The shortest path problem is about finding a path between  vertices in a graph such that the total sum of the edges weights is minimum. This problem could be solved easily using (BFS) if all edge weights were, but here weights can take any value. Three different algorithms are discussed below depending on the use-case. https://www.hackerearth.com/practice/algorithms/graphs/shortest-path-algorithms/tutorial/

```
vector <int> v [2000 + 10];
    int dis [1000 + 10];

    for(int i = 0; i < m + 2; i++){

        v[i].clear();
        dis[i] = 2e9;
    }

   for(int i = 0; i < m; i++){

        scanf("%d%d%d", &from , &next , &weight);

        v[i].push_back(from);
        v[i].push_back(next);
        v[i].push_back(weight);
   }

    dis[0] = 0;
    for(int i = 0; i < n - 1; i++){
        int j = 0;
        while(v[j].size() != 0){

            if(dis[ v[j][0]  ] + v[j][2] < dis[ v[j][1] ] ){
                dis[ v[j][1] ] = dis[ v[j][0]  ] + v[j][2];
            }
            j++;
        }
    }
```
[Code link](https://www.hackerearth.com/practice/algorithms/graphs/shortest-path-algorithms/tutorial/)