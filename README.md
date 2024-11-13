*This is a template repository for this organization. Start by replacing the placeholder for the project name with its actual title.*

# [Testing of Intelligent robot-assembly workplace for the production of bag filters in Vado Filters OÜ]

## Summary
| Company | [Vado Filters OÜ] |
| :--- | :--- |
| Development Team Lead Name | [Tõnu Lelumees] |
| Development Team Lead E-mail | [tonu.lelumees@imecc.ee](mailto:email@example.com) |
| Duration of the Demonstration Project | 11/2023-08/2024|
| Final Report | [Example_report.pdf](https://github.com/ai-robotics-estonia/_project_template_/files/13800685/IC-One-Page-Project-Status-Report-10673_PDF.pdf) |

### Each project has an alternative for documentation
1. Fill in the [description](#description) directly in the README below *OR*;
2. make a [custom agreement with the AIRE team](#custom-agreement-with-the-AIRE-team).

# Description
## Objectives of the Demonstration Project
*Please describe your project objectives in detail.*

To validate a concept and principles for the development of a flexible robotic assembly workplace for handling non-form-retaining textile materials as well as experimental workplace model for assembly of bag filters.

## Activities and Results of the Demonstration Project
### Challenge
*Please describe challenge addressed (i.e, whether and how the initial challenge was changed during the project, for which investment the demonstration project was provided).*

The main activities were concentrated to the validation of a smart and flexible robotic workplace for the assembly of filter bags. 
At first, solution for robotization was proposed following the principles of manual assembly. Soon it was clear that following the principles of manual assembly, it is not possible to achieve considerable results in productivity and the process of robotic assembly will be complicated. At a very early stage, it became clear that the existing filter solution was not suitable for robotic assembly. Therefore, Vado Filters OÜ designed a new frame solution (using DMF – design for manufacturing – principles), a 3D model was proposed and a new frame prototype was printed. Vado Filters plans to patent the new frame.
Then robot grippers for the new frame as well as the essence of assembly process were redesigned.
Additional investments in development the filter assembly frame for using  EOAT system concept to form a physical model of the workplace and test it were made by the company itself outside the demo project budget


### Data Sources
*Please describe which data was used for the technological solution.*  
- Vado Filters OÜ production layout,
  Technical task description (company’s objectives),
- Test bag filter system selected as a prototype,
- Filter bags 3D model,
- Final assembly principles,
- Industrial robot / Cobot technical data,
- Selected cobot technical data,
- Cobot control system technical data,
- Standard end effectors technical data,
- Needs for flexibility (reconfiguring),
- Smart workplace needs,
- Safety standard needs (to consider).

### AI Technologies
*Please describe and justify the use of selected AI technologies.*
- AI in this field is used for creating intelligent robot-based assembly workplace that work and react like human. There are two main areas: to understand the position of a filter-bag and correspondingly to determine the needed movements of the robot and the second, depending on the measures and material of filter bag to determine the needed power for EOAT to press with robot the two sides of filter frame together. This is an area of machine learning where decisions have been made based on big data and knowledge acquisition algorithms. The implementation of this in the real world gives explosive and broader use of robot in this case. 

### Technological Results
*Please describe the results of testing and validating the technological solution.*

1.	Understanding of the principles for handling of textile materials that do not keep their shape 
2.	Development of a prototype of an intelligent and flexible assembly robot system and testing its working principles
3.	Development of the grippers with needed functionality and testing them in real conditions
4.	Designed the final product for robot assembly – designed new filter bags’ holding frame and manufactured it with 3D printing
5.	Understand how to make the robot assembly system smart and flexible what would work like human being
6.	Designed the user-interface and used it for manipulating robot in a robot assembly cell
Conclusion: Testing showed that the technological solution for robot-assembly of bag filters which was achieved for the end of the project was successful. This was the first robot-based operation. To carry out the robot-assembly process completely, it is planned to robotize also the second operation – fixing upper and lower frame with the filter bags. Then the final solution  could be implemented industrially.

### Technical Architecture
*Please describe the technical architecture (e.g, presented graphically, where the technical solution integration with the existing system can also be seen).*
The main elements of the workplace for robot assembly of bag filters are:
-	the assembly robot UR 10 (Universal Robots cobot type UR 10 was used), 
-	the table for positioning the filter bags to be assembled, 
-	the jig for fixing the bottom of the frame and bag filters guide and 
-	needle grippers with possibility to dimension the grip force (not to damage the bags to be assembled). 
These elements for assembly workplace were developed physically during the project. Also, assembly workplace as a whole was developed considering the optimization of the robot’s working cycle.  

![backend-architecture](https://github.com/ai-robotics-estonia/_project_template_/assets/15941300/6d405b21-3454-4bd3-9de5-d4daad7ac5b7)


### User Interface 
*Please describe the details about the user interface(i.e, how does the client 'see' the technical result, whether a separate user interface was developed, command line script was developed, was it validated as an experiment, can the results be seen in ERP or are they integrated into work process)*

In this solution, the cobot UR10 user interface was used to control the robot's work cycle for assembly operations. 
The plan is to develop an integrated user interface based on various external devices (sensors, cameras) to ensure intelligent control of the robot, similar to actions performed by humans.

### Future Potential of the Technical Solution
*Please describe the potential areas for future use of the technical solution.*
- Assembly systems with intelligent grippers
- Filter bags assembly systems development
- Textile industry, for example for sewing pillowcases and bed sheets.

### Lessons Learned
*Please describe the lessons learned (i.e. assessment whether the technological solution actually solved the initial challenge).*

Specific robotic assembly tasks are highly multifaceted and many inputs are integrated with each other, directly affecting the end result.
The team had no previous experience in drafting processes with a free-form approach, and it is also rarely discussed in the literature and there is not widely used practical solutions in this topic.
It was possible to decompose the assembly process into parts and define the inputs and outputs of the stages to achieve the final result.
The final result achieved in the project is promising, although further progress is needed to reach the goal. The task turned out to be much more difficult than the available resources allowed.
The parties also made additional investments into the solution, and the company has a very strong desire to move forward with the robotization of the assembly process.


# Custom agreement with the AIRE team
*If you have a unique project or specific requirements that don't fit neatly into the Docker file or description template options, we welcome custom agreements with our AIRE team. This option allows flexibility in collaborating with us to ensure your project's needs are met effectively.*

*To explore this option, please contact our demonstration projects service manager via katre.eljas@taltech.ee with the subject line "Demonstration Project Custom Agreement Request - [Your Project Name]." In your email, briefly describe your project and your specific documentation or collaboration needs. Our team will promptly respond to initiate a conversation about tailoring a solution that aligns with your project goals.*
