[pdf link](https://github.com/schadr/ChatToSucceed/blob/master/thesis.pdf)

## Abstract
Efficient coordination among software developers is a key aspect in producing high quality software on time and on budget. Several factors, such as team distribution and the structure of the organization developing the software, can increase the level of coordination difficulty. However, the problem runs deeper as it is often unclear which developers should coordinate their work.

In this dissertation, we propose leveraging the concept of socio-technical congruence (which contrasts coordination needs with actual coordination) to improve the social interactions among developers by devising an approach and its implementation into a recommender system that identifies relevant coordinators. Our unit of analysis is the integration build, whose outcome represents the quality of coordination. After development, this approach was applied in a number of IBM Rational Team Concert development team case studies, as well as a large student project at the University of Victoria, Canada, and Aalto University, Finland.

Since each software product is just the latest integration build, it is of utmost importance for the industry to ensure a failure free build. While developing an approach to improve coordination among software developers we uncovered that unmet coordination needs, as well as the communication structure in a team, have a significant influence on build outcome.

## Table of Contents
1. Introduction 1
    1. ProblemStatement .............................. 3
    2. DissertationFocus............................... 4
    3. Contributions ................................. 5
        1. Approach ............................... 5
        2. EmpiricalFindings .......................... 6
    4. Overview ................................... 7
2. Background 10
    1. BuildOutcome ................................ 10 
        1. Communication, Coordination and Integration ............ 11 
        2. Cancommunicationpredictbuildfailure? .............. 12
    2. CoordinationinSoftwareEngineeringTeams ................ 13
        1. TheNeedforCoordination ...................... 13
        2. CoordinationinSoftwareTeams ................... 14
    3. Socio-TechnicalCongruence ......................... 15 
        1. Socio-TechnicalCongruenceDefinitions ............... 15 
        2. Socio-Technical Congruence and Performance ............ 18
    4. NetworksandFailure ............................. 19 
        1. ArtifactNetworks........................... 19 
        2. TechnicalNetworks.......................... 20
    5. RecommendationsinSoftwareEngineering ................. 20
    6. ResearchQuestions .............................. 21
    7. Summary ................................... 23
3. Methodology and Constructs 24
    1. MethodologyRoadmap............................ 24
        1. RQ 1.1: Do Social Networks influence build success? 24
        2. RQ 1.2: Do Socio-Technical Networks influence build success?............................... 26
        3. RQ 2.1: Can Socio-Technical Networks be manipulated to increase buildsuccess? .................... 27
        4. RQ 2.2: Do developers accept recommendations based on software changes to increase build success? ........... 27
        5. RQ 2.3: Can recommendations actually prevent build failures? .............................. 28
    2. Definitions................................... 29 
        1. WorkItem............................... 29 
        2. Change-Set .............................. 29 
        3. Build ................................. 30
    3. Constructs................................... 30 
        1. SocialNetwork ............................ 32 
        2. TechnicalNetwork .......................... 33 
        3. Socio-TechnicalNetwork....................... 34
    4. DataCollectionMethods ........................... 36 
        1. RepositoryMining .......................... 36 
        2. Surveys ................................ 37 
        3. Observations ............................. 37
        4. Interviews............................... 38 
    5. Summary ................................... 40
4. IBM Rational Team Concert 41
    1. TheIBMRationalTeamConcertProduct .................. 41 
        1. SourceControl ............................ 43 
        2. WorkItems .............................. 43 
        3. Planning................................ 45 
        4. BuildEngine ............................. 46 
        5. Foundation/Integration ........................ 46
    2. The IBM Rational Team Concert Product Development Team ........ 47 
        1. ThePeople .............................. 47 
        2. TheProcess.............................. 49
    3. Summary ................................... 51
5. Communication and Failure 53
    1. Methodology ................................. 54 
        1. Coordinationoutcomemeasure.................... 54 
        2. Communicationnetworkmeasures.................. 54 
        3. Datacollection ............................ 58
    2. AnalysisandResults ............................. 58 
        1. Individual communication measures and build results ........ 59 
        2. Predictive power of measures of communication structures ..... 60
    3. Discussion................................... 62
    4. Summary ................................... 62
6. Socio-Technical Congruence and Failure 64
    1. CalculatingCongruence............................ 65
    2. AnalysisMethods............................... 65
    3. Results..................................... 66
        1. EffectsofCongruenceonBuildResult ................ 68 
        2. EffectofGapRatioonBuildResult ................. 69
        3. Social and Technical Factors in RTC Affecting Build Success and Congruence.............................. 70
    4. Discussion................................... 73 
        1. StrongAwarenessHelpsCoordination ................ 75 
        2. Coordination and Geographic Distribution .............. 77 
        3. ProjectMaturityandBuildSuccess ................. 78
    5. Summary ................................... 79
7. A Socio-Technical Congruence Approach to Improve Build Success 80
    1. Overview ................................... 80 
    2. DefineScope ................................. 81 
    3. DefineOutcome................................ 81 
    4. ConstructSocialNetworks .......................... 81 
    5. ConstructTechnicalNetworks ........................ 81 
    6. GenerateInsights ............................... 82 
    7. Summary ................................... 82
8. Leveraging Socio-Technical Networks 85
    1. Socio-TechnicalCoordination ......................... 85 
    2. AnalysisofSocio-TechnicalGaps ...................... 86 
    3. Results..................................... 88 
    4. Discussion................................... 90 
    5. Summary ................................... 92
9. Acceptability of Recommendations 93
    1. StudyDesign ................................. 93 
        1. DataCollection............................ 94 
        2. Analysis................................ 99
    2. Findings....................................100
        1. DevelopmentMode..........................100
        2. Perceived Knowledge of the change-set Author ........... 103
        3. CommonExperienceandLocation..................104
        4. RiskAssessment ...........................105
        5. WorkAllocationandPeerReviews..................106 
        6. TypeofChange............................106 
        7. BusinessGoalsvsDeveloperPride..................107
    3. Summary ...................................107
10. Appropriateness of Technical Relations 109
    1. A Course on Globally Distributed Software Development .......... 109 
        1. CourseDetails ............................111 
        2. TeamComposition ..........................112 
        3. DevelopmentProject .........................112 
        4. DevelopmentProcess.........................113 
        5. IT-Infrastructure............................113
    2. Methodology .................................114 
        1. Proximity to Infer Real Time Technical Networks .......... 114 
        2. Data Collection ............................ 114 
        3. Analysis................................116
    3. Findings .................................... 117 
        1. BuildFailuresThatMatter ......................117 
        2. PreventableBuildFailures ......................118 
        3. TheRightRecommendations.....................118
    4. Discussion ................................... 120
    5. Summary ...................................120
11. Conclusions
    1. AnApproachForImprovingSocialInteractions ...............122
    2. ContributionsthroughEmpiricalStudies ...................124
         1. Using Build Success as Communication Quality Indicator .....124
         2. UnmetCoordinationNeedsMatter..................125 
         3. DevelopersThatInduceBuildFailures ................ 125 
         4. RecommenderSystemDesignGuidelines .............. 126 
         5. Socio-TechnicalCongruenceinRealTime .............. 128
    3. Threats to Validity ............................... 128
    4. Future Work .................................. 130
        1. Implement and Deploy the Recommender System .......... 131
        2. Extendthe Recommender System with more Technical Dependencies 131
        3. Extend the Recommender Systemby Generalizing the Recommendations 132
        4. Investigate Architectures that Better Fit Organizational Structures . 132
