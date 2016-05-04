#University of Southampton
##Msc Artificial Intelligence
###COMP6216 Simulation Modelling for Computer Science

`Problem Description`
1. A population of students is working on group projects. Students can follow two strategies (S): work hard for the project (S=H) or free-ride (S=L).
2. In every course, groups of size n are formed at random. Students use the strategy determined at the beginning of the course (i.e. S=H or S=L) in their group work.
3. Total group effort is determined by the composition of the group. In a group with h hard workers and l=n-h lazy workers total group effort is e=h*H+l*L (H and L being the effort put in by hard/lazy workers).
4. When group projects are marked, every student gets the same mark. The lecturer determines this mark as m=e/n (i.e. by dividing total group effort by the number of students in a group; the larger this number the better the mark)
5. At the end of the semester every student rethinks his strategies for the next semester. He does this, by selecting another student at random and comparing a measure π based on marks and effort, π=m-a*S (where a is a parameter and S=H or S=L depending on strategy). The measure accounts for the mark obtained, but is lowered by the amount of effort spent. Very good marks without effort maximise the performance measure. If the student selected for comparison got a higher performance measure π, the reference student will imitate the reference student's strategy with a probability proportional to the difference in performance measures. In case the comparison student got a lower measure, the first student does not change his strategy.
6. Students study forever (i.e. take an infinite number of courses) and follow the same procedure (as outlined above) for every course they take.
Research questions to address:
7. Assuming we start with equal numbers of hard working students and lazy students, what is the composition of the group
··*After 4 years (i.e. 8 courses) if H=1 and L=0 and a=0.5. ··*In the long run (after an “infinite” number of years)?
··*How quickly is this equilibrium state reached?
8. How do the following parameters influence results: 
··*Initial composition of the population
··*Group size (n)
··*Cost of effort a
··*Contribution of hard workers to group effort (i.e. H and L)