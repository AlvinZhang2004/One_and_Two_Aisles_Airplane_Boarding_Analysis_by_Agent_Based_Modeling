# One-and-Two-Aisles-Airplane-Boarding-Analysis-by-Agent-Based-Modeling
 we summarized several previously proposed methods in one aisle airplane boarding process. We used  Agent-Based Modeling to reconstruct these models and analyzed the boarding  efficiency of these models. We also constructed the two axles airplane and designed several original boarding methods.

<img width="636" alt="302443dcc5586ed47bc3ba740db804a" src="https://user-images.githubusercontent.com/115446996/194825261-bd9700a0-b552-4ab8-80f3-fadf6f52d972.png">
one aisle airplane boarding model

<img width="719" alt="556ae60a562a323a83748a21c2385a9" src="https://user-images.githubusercontent.com/115446996/194824727-922a8e55-855c-46f9-a6ff-53b38a8675a1.png">
two aisles airplane boarding model

Boarding methods of one aisle airplane boarding model:

- Random Model

The random model assigns seats for passengers in complete randomness, without any prescribed methods.

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/92247623/194847327-d88990e1-e4ee-4ce0-b59b-d3527ba91a2c.gif)

- By Seat Model

The by seat model allows passengers with seat row numbers A and F to board first, then B and E, and finally C and D.

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/92247623/194857541-0f7ccbb0-cb24-488e-9d2e-715a1e3c3b15.gif)


- By Section Model

The by section model allows passengers to board in five groups, with seat column numbers 25-30 board first, then 19-24, 13-18, 7-12, and finally 1-6.
The by section method does not control the passengers’ row number (A to F), and passengers are randomly assigned with their exact column number within the range of the group.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/92247623/194842797-f81d7c10-a157-4388-a0c1-25e15d616592.gif)

- Steffen Model

The Steffen model is constructed originally by Jason Steffen in 2008. The Steffen method is, by far, the most efficient boarding method, tested through mathematical models under ideal conditions where people do not have requirements to sit together or board together, and everyone follows the designated boarding sequence with no complaints.

The method files people into a plane in a straight line, and people are seated in the following order, from back to front:

Window seat, odd-numbered. 

Window seat, even-numbered. 

Middle seat, odd-numbered. 

And so on.

![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/92247623/194858058-4f067665-47f2-4960-8d46-f246cc6e74b3.gif)

- Enhanced Steffen Model

We found a weakness in the Steffen model: passengers who take bags might block people who don't. Therefore, we made a little improvement on the previous model. By using the same boarding method but letting passengers who take luggage board the plane at first, we successfully improved the model's efficiency.

![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/92247623/194858024-d85af13c-7d18-42d4-946b-0ccd0403ff3f.gif)

- Humanitarian Model

The Humanitarian method considers a more realistic demand of the passengers— —families and friends want to board and sit together. To take into account the factor while minimizing the changes on the fastest model, the Humanitarian method allows three passengers for the same row same side to board at one time in the sequence of inside-out. Other aspects of the original Steffen method are not revised.

![ezgif com-gif-maker (7)](https://user-images.githubusercontent.com/92247623/194857957-7e1459f2-9b59-4d93-8576-da1cf6c4d22d.gif)


Boarding methods of two aisles airplane boarding model:

- Random Model

Similar to the previous random model, passengers are assigned seats randomly. However, the distinction is that in this model, passengers with seats in the upper rows (A, B, and C) will go to the upper axle, while passengers with seats in the lower rows (E, F, G) will go to the lower axle, as stated in the update assumptions part. Therefore, passengers will not need to cross from one axle to the other.

![ezgif com-gif-maker (5)](https://user-images.githubusercontent.com/92247623/194858329-6c395c99-063b-4261-a3fc-5b7409af36fa.gif)

- By Seat Model

In the by seat model, passengers have divided into four groups: the first boarding group is passengers with seats in rows A and G, the second boarding group are passengers with seats in rows B and F, the third boarding group is passengers with seats in row D, and the last boarding group is passengers with seats in rows C and E.

![ezgif com-gif-maker (10)](https://user-images.githubusercontent.com/92247623/194861438-748b4a64-66ae-4326-8c27-179a55afa8d3.gif)

- By Section Model

In the by section model, passengers have divided into five groups: the first boarding group is passengers with seats in columns ranging from 25 to 30, the second boarding group is passengers with seats in columns ranging from 19 to 24, the third boarding group is passengers with seats in columns range from 13 to 18, the fourth boarding group is passengers with seats in columns range from 7 to 12, and the last boarding group is passengers with seats in columns range from 1 to 6. 

![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/92247623/194857784-72e9a222-e2d5-4a99-ba9d-900169add06a.gif)

 - Steffen Model

The mechanism of the Steffen model is as same as the previous model. People will seat one row apart from each other the first time and then seat the empty seats between them. 

![ezgif com-gif-maker (8)](https://user-images.githubusercontent.com/92247623/194860588-c069b8a5-992c-4365-8201-1a4453925ab5.gif)

- Outside-in Model

Passengers sit from back to front and from window to the middle at the same time. 

![ezgif com-gif-maker (9)](https://user-images.githubusercontent.com/92247623/194860347-76062226-0bf7-4d5f-98db-4bfeea7dfe47.gif)

References

Giitsidis, T., & Sirakoulis, G. C. (2016). Modeling passengers boarding in aircraft 
using cellular automata. IEEE/CAA Journal of Automatica Sinica, 3(4), 365–
384. https://doi.org/10.1109/jas.2016.7510076 

Mansurova, D. (2016, January 15). Aircraft Boarding Methods. Aircraft boarding 
methods - Simulace.info. Retrieved June 23, 2022, from 
http://www.simulace.info/index.php?title=Aircraft_boarding_methods&action=
edit&redlink=1
