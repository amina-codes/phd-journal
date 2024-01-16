My understanding of the “little languages” from a technical perspective is that they can make one’s coding experience better. Is that their only requirement? Clarity and ease of use? Judging on these two criteria, I had several “easy” and “clear” coding experiences that made my life better (and faster).

1. Python.

I must admit, I only learned Python after I knew some foundational programming concepts and after learning C++. In that sense, I was surprised to learn how fast and efficient it is compared to, for example, constantly and annoyingly allocating memory/space/etc.

What one can do with more than 10 lines of C++ code, Python can do in just 1 (well, thanks to the built-in features and libraries):
```
a = (1, 11, 2)
x = sorted(a)
print(x)
```

vs.


```
// C++ program to demonstrate descending order sort using

// greater<>().

#include <bits/stdc++.h>

using namespace std;


int main()

{

int arr[] = { 1, 5, 8, 9, 6, 7, 3, 4, 2, 0 };

int n = sizeof(arr) / sizeof(arr[0]);

sort(arr, arr + n, greater<int>());

cout << "Array after sorting : \n";

for (int i = 0; i < n; ++i)

cout << arr[i] << " ";

return 0;

}
```


2. Processing.

A couple of folks already mentioned Processing, so I won’t spend too much time explaining what that is. I will just point that inside of Processing too, there are versions that are easier and more efficient yet produce the same graphical output. For example, p5.js (a version of Processing that eventually became an independent piece), in my observation, is easier in UX than Java Processing. In the same way, Python Processing > Java Processing (partly also because Java is like C++ and requires a lot of allocation/memory/space work compared to js or py).

```
function setup() {

  createCanvas(400, 400);

}
```


```
function draw() {

  background(220);

  // Draw a rectangle

  rect(50, 50, 100, 80);
  
}
```

3. Slang.

In “Little Languages”, a lot of the context comes from the programming experience in the 1990’s. During that time, an investment bank on Wall street developed their own “little language” based on C++ to make their operations more secure and their programmers happier. Fast-forward to 2022, I was interning in this firm, and the “little language” (called Slang, for Securities LANGuage) was still alive, up, and running. As you can see, I am not the biggest fan of C++, but it took me less than 2 weeks to became proficient at Slang and even start writing some sensible code. Unfortunately, I cannot share any snippets of code as I’ve lost access to them, but Slang, to me, is a version of C++ if Python and C++ had a baby. :D

Overall, if we were to simplify this, what is the greatest difference between a "little language" and, say, a library? Both can make the coding UX easier and more efficient. Then, is there another definition of a "little language" that I do not understand?


# 👩🏻‍💻 phd-journal
PhD work + accountability journal

# Week 3: Oct 16-20, 2023

Tue:
- got some Arduino things from the SET lab
- lit review additions
- checking unity but no significant progress on that front yet
- class work

# Week 2: Oct 9-12, 2023

Ok, I almost thought I'd skipped a week -- this is how already busy my mind is... But! Significant progress this week to the project onboarding with Unity and catching up with all of the technical details of the lab projects. Also met with my advisor 1:1 and discussed a plan for starting my funding applications. As always, need to get a gew things ready for those and also take a mental note about two personal projects happening at the same time.

To Do:
- [ ] Request two reference letters
- [ ] Write essay responses
- [ ] Lit review for the new project -> also helpful for the above
- [ ] Unity troubleshooting for the lang. localization
- [ ] 201 HW
- [ ] Schedule two meetings for the personal projects
- [ ] Find out if there's a space to test Arduino stuff @ UCSC
- [ ] Do a p5 refresher when the time comes

# Week 1: Oct 2-6, 2023

## Tasks Completed:
- [x] Lab meeting
- [x] Class readings and responses: 201
- [x] Weekly postdoc meeting 

## Next week TBD:
- [ ] Past grant application review
- [ ] Lit review for grant update
- [ ] 201 hw
- [ ] Career fair at SVC
- [ ] Weekly postdoc meeting
- [ ] Decorate + clean the lab space

## Reflections:

- Research = expanding your engineering work to be more intentional and critical.

# Week 0: Sep 27-30, 2023

## Tasks Completed:
- [x] CITI training for the IRB approvals
- [x] Class work: 201, 243 (ended up postponing it to next quarter)
- [x] Postdoc meeting regarding project handover  

## Next week TBD:
- [ ] Unity project troubleshooting (localization and multiplayer issues)
- [ ] Readings and responses 201
- [ ] Lab meeting
