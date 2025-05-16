# Design review Plan

## Evaluation Approach Decision

**Selected Approach:** Heuristic Evaluation

**Number of Evaluations:** Each member will conduct 3 evaluations

**Evaluation Combinations:**
  - Adam: Nagare, Philip, Josh
  - Nagare: Ben, Anthony, Adam
  - Ben: Philip, Josh, Anthony
  - Philip: Adam, Nagare, Ben
  - Anthony: Josh, Adam, Philip
  - Josh: Anthony, Ben, Nagare

## Template Selection

**Selected Template:** [Figma Template](https://www.figma.com/community/file/905622673082476274)

Create our own evaluation table to consolidate findings.
reference: [Example](https://www.researchgate.net/publication/340895224_Usability_evaluation_of_a_comprehensive_national_health_information_system_A_heuristic_evaluation)

**Table used:**
Design Review table.xlsx

The table in the reference had serious problems:
- Only show the average severity, but not calculation method
- No clear explanation of the severity rating
- Either the calculation is wrong or calculation logic to each heuristic is inconsistent

Therefore, we used more logical and intuitive calculation method.  
Our design review used the following severity rating system:  
SEVERITY:  
0 = I don't agree that this is a usability problem at all  
1 = Cosmetic problem only: fix if time is available  
2 = Minor usability problem: fixing this should be given low priority  
3 = Major usability problem: important to fix, given high priority  
4 = Usability catastrophe: fix this before product can be released  

We assigned the coefficients to each severity rating as follows:
- None = 0
- Cosmetic = 1
- Minor = 2
- Major = 3
- Catastrophe = 4

The average severity is calculated as follows:
- Severity rating = number of evaluation * coefficient
for each severity rating category.
- Average severity = (sum of severity ratings) / (number of heuristics evaluated)

To be more specific:
Average severity = (number of None * 0 + number of Cosmetic * 1 + number of Minor * 2 + number of Major * 3 + number of Catastrophe * 4) / (number of heuristics evaluated)

where number of heuristics evaluated is always 3. (3 heuristics per evaluation) 


## Heuristics to Be Used
Nielsen's 10 Usability Heuristics:
1. Visibility of System Status
2. Match between the System and the Real World
3. User Control and Freedom
4. Consistency and Standards
5. Error Prevention
6. Recognition Rather than Recall
7. Flexibility and Efficiency of Use
8. Aesthetic and Minimalist Design
9. Help Users Recognize, Diagnose, and Recover from Errors
10. Help and Documentation

Reference: [Nielsen Norman Group - 10 Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/)

## Evaluation Timeline
- Date for distributing evaluation templates: May 8, 2025, 8:00 PM
- Deadline for individual evaluations: Ideally by May 11, 2025, 8:00 PM
- Date for consolidating findings: Ideally on next meeting
- Date for presenting results: Ideally on next meeting

**Next Meeting:** May 11, 2025, 8:00 PM -> 1 hour
**Next Meeting:** May 16, 2025, 2:00 PM


### Links:

[Part 1 Handout](https://ecs.wgtn.ac.nz/Courses/SWEN303_2025T1/GroupProjectPart1)

[How to Conduct a Heuristic Evaluation](https://www.nngroup.com/articles/how-to-conduct-a-heuristic-evaluation/)

[Heuristic Evaluation](https://www.interaction-design.org/literature/topics/heuristic-evaluation)

[Paper Prototyping](https://alistapart.com/article/paperprototyping/)

[sum up table example](https://www.researchgate.net/publication/340895224_Usability_evaluation_of_a_comprehensive_national_health_information_system_A_heuristic_evaluation)
