# Online Exam Face Detection (OeFD)
# PROJECT OVERVIEW
## A. DEFINING THE PROJECT
### :floppy_disk: Project Summary

Customer: University Students (Mock)

Project name: Online exam Face Detection (OeFD) 

Team Members:
Name                                | Matrics Number          | Role                    |             
----------------------------------  | ----------------------- | ----------------------- |
Nurul Aishah binti Mohd Zaini       | B031910009              | Project Manager         |
Nurul 'Izzah binti Muhammad Zawave  | B031910128              | Programming Engineer    |
Siti Kamariah binti Ismail          | B031910052              | Financial Analyst       |
Thanushaini A/P Poobalan            | B031910159              | Human Resource Manager  |  


### :scroll: Objectives
* Identify registered students by using face recognition
* Improve security during online exams 
* Promote honesty among students

## B. PLANNING THE PROJECT
### :clipboard: Project Management Life-Cycle
| ![gantt chart](https://user-images.githubusercontent.com/85090534/147879194-da37f5c1-bb40-458e-a8c6-c95a79e9b415.png) |
|:--:| 
| *Figure 1: Gantt Chart* |

| ![WBS](https://user-images.githubusercontent.com/85090534/147879599-5289bb4b-eba6-4c23-86fa-8956cb114459.PNG) |
|:--:| 
| *Figure 2: Work Breakdown Structure* |

### :scroll: Responsibility Assignment Matrices (RAM) :
| ![RAM(part1)](https://user-images.githubusercontent.com/85090534/148410584-47082a0b-c6b3-475c-9d93-cc84acf55894.PNG) |
|:--:| 
| *Figure 3: Responsibility Assignment Matrices I* |

| ![RAM(part2)](https://user-images.githubusercontent.com/85090534/148410877-381c8065-69ee-41ed-bc99-184fcb25df84.PNG) |
|:--:| 
| *Figure 4: Responsibility Assignment Matrices II* |


### :memo: Project Planning Summary :
Modules/Components                  | Budget (RM)                | Schedule                            | Responsibility                | 
----------------------------------  | -------------------------- | ----------------------------------- | ----------------------------- |
Student's Face Database             | 250,000.00                 | 15 November 2021 - 25 November 2021 | Collect & Label Data          |
Student Face Recognition            | 1,2000,000.00              | 1 December 2021 - 31 December 2021  | Training & Testing Data       |
Online Exam Website                 | 600,000.00                 | 15 December 2021 - 5 January 2022   | Web Development & Integration |

## C. IMPLEMENTING THE PROJECT PLAN
### :book: Deliverables
* Planning Deliverables
* Analysis Deliverables
* Design Deliverables
* Implementation Deliverables

### :pushpin: Estimated Costs and Tasks
Task                                | Estimated Cost (RM)        | Comments                            | 
----------------------------------  | -------------------------- | ----------------------------------- | 
Acquisition                         | 1,318,157.50               | Software, Hardware, Data Collection |
Design                              | 119,000.00                 | System Design, Training & Testing   |
Restoration                         | 985,279.00                 | System Installation, Maintenance    |

### :date: Milestone Chart
Milestone                           | Scheduled Completion       | Actual Completion                   | 
----------------------------------  | -------------------------- | ----------------------------------- | 
Planning                            | 21 October 2021            | 30 October 2021                     |
Analysis                            | 15 November 2021           | 20 November 2021                    |
Design                              | 31 December 2021           | 29 December 2021                    |
Implementation                      | 5 January 2022             | 10 January 2022                     |

## D. EXECUTING THE PROJECT 
### :open_file_folder: Project Design and Coding
### Flow Diagram
| ![flow_diagram](https://user-images.githubusercontent.com/85090534/150286494-4166fa11-c0f1-418d-8448-0132f8e02642.jpg) |
|:--:| 
| *Figure 5: Flow Diagram* |

### :page_facing_up: CODING:
- Library packages needed:
- 
| ![Library packages](https://user-images.githubusercontent.com/85090534/149967328-07ff3d6d-900a-4965-b313-225364fe4a44.PNG) |
|:--:| 
| *Figure 6: List of library packages needed* |

- Steps needed in order to successfully install face_recognition package
  - Step 1: pip install cmake
  - Step 2: pip install dlib
  - Step 3: pip install face_recognition

|![Face Recognition](https://user-images.githubusercontent.com/85090534/149967776-5efe261b-17de-4683-88cb-f736386d0c0d.PNG)|
|:--:| 
| *Figure 7: Face Recognition algorithm* |
- For every face successfully detected by the algorithm by applying our trained model, a green bounding box is placed on the student's face with their name displayed. (Face Recognition)

|![Face Recognition 2](https://user-images.githubusercontent.com/85090534/149968025-4771d2d7-f4f1-436f-89dd-84fc9f8d9b18.PNG)|
|:--:| 
| *Figure 8: Record the date and time of student* |
- The time of when the student enters the hall and exits the hall is recorded and saved in a csv file, as well as the image captured and detected timely throughout the exam. 

### GUI CODING USING QT DESIGNER:
- Qt Designer is used in creating the app interface for student's face detection before entering the virtual exam hall

|![GUI main interface framework](https://user-images.githubusercontent.com/85090534/149968380-93ecf950-e246-4f40-8aaf-bf61b1b18ad7.PNG)|
|:--:| 
| *Figure 9: GUI framework for the interface* |

### :page_facing_up: PROJECT RESULT:

- Result 1: student's face detected, student can proceed to enter the exam hall

![Result1](https://user-images.githubusercontent.com/85090534/150289985-d343be73-b30c-4091-be36-6ea6e3c2dcab.PNG)


- Result 2: In the virtual exam hall, student's face is detected and authenticated in a timely manner using a timer

![Result2](https://user-images.githubusercontent.com/85090534/150290246-31e05eb3-7cee-428e-b410-b23c8809b914.PNG)


- Result 3: The time and duration spent in the exam hall is recorded in a csv file

![Result 3](https://user-images.githubusercontent.com/85090534/150290789-93ee3438-25c1-4d09-9eb6-e303bc5b9931.PNG)


![Result 4](https://user-images.githubusercontent.com/85090534/150290830-ee0d2cdb-d97d-4265-95d6-88a0fdba18eb.PNG)


## E. COMPLETING THE PROJECT
### :clipboard: Closing Checklist
:white_check_mark: [Sign Off](https://github.com/HummingBird39/Online-Exam-Face-Detection-OeFD-/blob/main/Project%20Documentation/11%20Project%20Sign%20Off.pdf)



:white_check_mark: [Lesson Learned](https://github.com/HummingBird39/Online-Exam-Face-Detection-OeFD-/blob/main/Project%20Documentation/10%20Project%20Closing.pdf)



:white_check_mark: [Final Project Report](https://github.com/HummingBird39/Online-Exam-Face-Detection-OeFD-)



:white_check_mark: [Closing Contract](https://github.com/HummingBird39/Online-Exam-Face-Detection-OeFD-/blob/main/Project%20Documentation/10%20Project%20Closing.pdf)

## F. PROJECT PRESENTATION
### :round_pushpin: Presentation & System Demonstration Video
* Click the video below to watch our presentation and system demonstration

### :round_pushpin: Presentation Slides
* Click the link below to view our presentation slides

