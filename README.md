# Drugs Book
Graph of drugs and diseases they treat, providing a larger set of use cases of drugs beyond their singular clinical use. 

This project is trying to accomplish graphing different drugs (intially 10) along with their use cases (10) and diseases they treat, by doing so we are able to see a drugs multiple use cases beyond the clinically approved single use. 

Presentation: https://www.youtube.com/embed/nXYcaM1artU

Factors:-
1. Impact: with increase in data (both in number and in use cases) we can see several uses cases for several drugs (from most used to rarely used). 
2. Innovation: graph allows easy creation of base model and addition of data. 
3. Ambition: system encompassing thousands of drugs where alternatives to almost every drug can be found. 
4. Application: doctors can utilize this (with larger data) to prescibe cheaper (economic value) but still effective drugs (based on clinical studies).

Other:-
1. Data: 10 files are given in the resources folder. 
2. Technology: sole usage of TigerGraph.

- Schema:-
![B](https://user-images.githubusercontent.com/104115795/164938778-ded825bd-3d02-4ecb-b31e-7db2fd0f4878.JPG)

- Loading:-
![C](https://user-images.githubusercontent.com/104115795/164938779-a6fbc72e-5491-4fbe-adac-449735ad527b.JPG)

- Insights:- 
![D](https://user-images.githubusercontent.com/104115795/164938780-45706bf5-1bca-4369-a6df-2486d8a851d9.JPG)

Dependencies:-
- A TigerGraph Cloud account is required.

Installation:-
*I will properly update this soon, i missed up alot with github so am fixing it, here is a basic overview*
1. Schema:-
   A) Create 2 vertices (Drug, Disease) with respective attributes (Title, Status, Result, Intervention, Location, URL) and (Title, Status, Result, Condition,   
   Location, URL). 
   B) Create directed edge with attribute (Location).
2. Mapping:-
   A) Download all the csv files from resources folder and import them into the TigerGraph Studio.
   B) Place them around the Scheme, match them with both vertices and the edge.
3. Loading: Press play until finished.
4. Exploring: View the insights through vertice expansion. 

Improvements:-
1. Better organization of data files that would reduce clutter as drugs are increase to 100-1k in number. 

Reflections:-
1. Being my first CS Project, alot of time was wasted trying to figure out by myself. I got a base once i found and viewed the tutorial by TigerGraph https://www.youtube.com/watch?v=czbOAG7ITz4&t=2258s. 

Thanks to:-
1. https://www.youtube.com/watch?v=czbOAG7ITz4&t=2258s tutorial for giving be a start to Graph and TigerGraph. 
2. https://clinicaltrials.gov/ for providing the data of clinical/other trials/studies of drugs. 
