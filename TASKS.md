This writing uses Markdown, for help go to [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

## Task 1
* Objective: analyze your industry and decide your primary and support activities
***
* Your company's name: BEAR
***
* Your company's NAICS (at least 4-digit) code and associated description from [NAICS Search](https://www.naics.com/search/):

*Important note: Your NAICS 4-digit code must start with 31, 32, or 33 (Manufacturing)*
  - Code: 327213
  - Description: This U.S. industry comprises establishments primarily engaged in manufacturing glass packaging containers.
  - Product: Focused on creating bottles with a unique design using 3D printing. Customers can request a customised design for their bottles.
***
* Corporate name and total employees of the top 3 businesses (Click To View Corporate Businesses by Revenue):
  - Owens-Illinois Inc, 26.500 employees
  - Certainteed LLC, 6.000 employees
  - Owens-Brockway Packaging Inc, 7.000 employees
***
* Number of businesses in your NAICS code from [Market Research](https://www.naics.com/market-research/): 278
***
* List of your company's primary activities divided into engineering activities and operations activities:
  - design of a bottle and the stupper 
  - Production with 3D printing  
  - transfer to container 
  - fixation of the packaging 
***
* List of your company's support activities:
  - human ressource management
  - technology development
  - planning, finance, legal,organisational structure
  - Procurement includes activities of purchasing the raw materials
***

## Task 2
* Objective: analyze and design your company's jobs using [ONET](https://www.onetonline.org/) 
***
### Managers
* ONET-SOC code and title: 11-2032.00 - Public Relations Managers
* 5 most important tasks they carry out (provide the importance score, in Details):
  - Assign, supervise, and review the activities of public relations staff.
  - Confer with labor relations managers to develop internal communications that keep employees informed of company activities. 
  - Design and edit promotional publications, such as brochures. See more occupations related to this task.
  - Develop and maintain the company's corporate image and identity, which includes the use of logos and signage.
  - Develop, implement, or maintain crisis communication plans.

* Is this job routine? Your judgment (0-10):
  - no, it is a very diversified function ! around 8/10 about routine (with a 0 as a totally routine job) 

* Is this job cognitive? Your judgment (0-10): 
  - it is a cognitive function! around 7/10

* 5 most important skills they require to possess (provide the importance score, in Details):
  - Management of Financial Resources — Determining how money will be spent to get the work done, and accounting for these expenditures.
  - Management of Material Resources — Obtaining and seeing to the appropriate use of equipment, facilities, and materials needed to do certain work.
  - Management of Personnel Resources — Motivating, developing, and directing people as they work, identifying the best people for the job.
  - Time Management — Managing one's own time and the time of others.

* 5 technology skills:
  - customer relationship management CRM software 
  - Data base user interface and query software
  - Desktop publishing software
  - Electronic mail software
  - Graphics or photo imaging software

* Education:
  - master in management (university or business school) 

* Wages:
  - Median wages (2019)	$55.86 hourly, $116,180 annual

* Top industry:
  - Educational Services and other Services (Except Public Administration)


### Engineers
* ONET-SOC code and title:
* 5 most important tasks they carry out (provide the importance score, in Details):
  - to encode 
  - the engineer must know the mechanism of the printer in order to manage any problem related to it
  - CAO design
- 
* Is this job routine? Your judgment (0-10):7
* Is this job cognitive? Your judgment (0-10):8
* 5 most important skills they require to possess (provide the importance score, in Details):
  - the research and development is the most important
  - -Basic knowledge of fluid mechanics and solid mechanics appreciated
  - the design of the product has to be improve with the engineer
  - manufacturing also should not be underestimated
- CA0 design and production in 3D printing of various pico-turbine prototypes
* 5 technology skills
  - to code is important because they have to encode printer actions
  - knowledge about 3D printer mechanism and composition
  - research and development
  - design, manufacturing, 
  - exploitation,expertise
* Education:
* Wages:$43,586/hour 
* Top industry: automotive and aerospace
### Operators
* ONET-SOC code and title: 
* 5 most important tasks they carry out (provide the importance score, in Details):
  - Assist in the installation, maintenance, and repair of machinery;
  - Operate tools in order to aid in the manufacturing process;
  - Perform periodic checks on equipment and solve problems as detected;
  - Work with others in order to ensure that equipment is in proper working order; 
  - Observe and follow company safety rules and regulations.
* Is this job routine? Your judgment (0-10): 9, because they install their machines, operate them to aid in plant processes, and perform routine maintenance checks
* Is this job cognitive? Your judgment (0-10):8, because the requirements are: High School Diploma/GED, a combination of additional education and experience. They must have some aptitudes for math, problem-solving, computers, and mechanics.

* 5 most important skills they require to possess (provide the importance score, in Details):
  - They should have attention to detail;
  - Ability to work and communicate well with others;
  - Proficiency with hand tools;
  - willing to perform repetitive tasks for extended periods; 
  - Help ensure that all safety regulations are followed.

* 5 technology skills: 
  - Programming languages
  - Data analysis
  - technical writing
  - Software proficiency
  - Common operating systems
  
* Education:
* Wages:
* Top industry:
***

## Task 3
* Objective: forecast your firm's number of available workers using Python (click the black button at the top of the README.md file)
***
You plan to start hiring workers next year. During this very first year, you are its only workers, all managers. Yearly staff movements were, on average, as follows: Out of 15 managers, 5 stayed in the same occupation, 5 moved to operators, and 5 left the firm; Out of 20 engineers, 10 stayed in the same occupation, 2 moved to managers, 5 moved to operators, and 3 left the firm; Out of 50 operators, 45 stayed in the same occupation and 5 left the firm. Using this information, predict how many managers, engineers, and operators you will have company will have in one year from now.
***
For the calculation we considered our group of people for the b matrix as: 1 manager, 1 engineer and 2 operators.
The result of the prediction are: 
- 0 Manager (0.43333333);
- 1 engeneer (0.5);
- 2 operator (2.38333333).
***
## Task 4
* Objective: forecast your firm's need for workers and anticipate mismatches using Python (click the black button at the top of the README.md file)
***
Last three years data on unemployment for managers was 15%, 17% and 14% for managers; 6%, 6%, 5% for engineers; and 23%, 27%, and 25% for operators. Last three years, the need for workers on average and per firm was 4, 6, 5 for managers; 13, 12, 13 for engineers; and 7, 7, 9 for operators. Using this information, predict how many workers your company will need in one year from now for each of its 3 occupations if unemployment is predicted to be 10% for managers, 4% for engineers, and 20% for operators. 

Last but not least, for each occupation, compare your predictions to anticipate mismatches
***

The results for the betas are [0,125 ; 3,0833 ; 11, 958 ; 4,591] 
We will need 4 managers (4,33) , 12 enginners (12,458) and 7 operators (7.04166).

***

## Task 5
* Objective: Post 1 job vacancy for each occupation to work on remote by describing the tasks and skills required. Use [Indeed](https://www.indeed.com/l-Remote-jobs.html) for help.
***
### Job posting for Managers:

BEAR is growing ! 
We're excited to announce that we're looking to extend our team, in order to improve our productivity and engagement toward our clients. 

Join us in our mission to elevate customer experiences for good-living people all around the globe. As a member of BEAR managing team, you will be part of a global experience company that believes in being people-first, celebrating diversity and incubating innovation. Our dedication to our purpose and people is being recognized by our employees and the industry.

For the manager position, we are only recruting four person, Will you be part of the team ? 

Position Purpose ? 
The manager in operations is responsible for the daily oversight and management of a team of supervisors charged with achieving client deliverables through high performance teams of customer care representatives.  The Manager also has significant client facing interaction. 

Job Requirements : 
- Monitor, track and evaluate supervisor performance based upon pre-determined Key Performance Indicators (KPI’s) and provide personal ongoing support and feedback to supervisors to ensure all client deliverables are met and Everise standards are adhered to. 
- Be a regular presence on the production floor and actively interact with supervisors and associates to ensure that they are engaged in productive work and systems are functioning properly
- Responsible for upward and downward communication both internally and as required to the client
- interact with clients demonstrating engaged leadership and detail orientation
- Responsible for creation and implementation of incentive programs

Who do we need ? 
- Master in Management graduated (business school or university) 
- sof skills : natural leader, excellent oral and written communication skills, rigor, hardworking, flexibility, multitasking, organized
- preferable experience in the filled of management

This job position comes with a 70 000E salary base, negociable according to the experience of the candidate.
The automation risk pourcentage is (NEED TO FIND THAT NUMBER !!!!!!!!). We will test the ability of the candidate to manage a team, through a serie of test in order to analyse his personality and his ability to work effectively in a time-limited environment. 

Are you a motivated, reliable and organised worker ? We're expecting you in BEAR ! 




### Job posting for Engineers:
BEAR is growing ! 
We're excited to announce that we're looking to extend our team, in order to improve our productivity and engagement toward our clients. 
Join us in our mission to elevate customer experiences for good-living people all around the globe. As a member of BEAR engineering team, you will have the chance to serve as a lead industrial engineering in data processing and coding. So join us in our mission to improve the way of making the bear beer bottle.
Position purpose:
An enterprise engineer's duties include implementing secure and scalable systems, drive tactical and strategic initiatives with product managers, build business performance metrics, and create interfaces for high-quality tools and complex systems. Also the engineer in our enterprise has to know how to code for the machines to make the design of the bottle perfectly.
Job Requirements : 
The engineer must be able to exercise creative thinking to devise new systems and innovative ways to work, he also msut be able to use standard equipment and tools necessary for the role. The engineer for our compagny has to know at least three different language in code for the make of the bottles. As we have 3D printer specialized in the making of our bottles the engineer must understand mechanical concepts and processes of the machines easily.
### Job posting for Operators:
***

## Task 6
* Objective: Create a website for your project
***
[GitHub Pages](https://pages.github.com/)
