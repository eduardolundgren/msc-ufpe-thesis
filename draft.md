1 Introduction 19
	1.1 Motivation................................. 19
	1.2 ProblemDefinition ............................ 19
	1.3 Objectives................................. 19
	1.4 ThesisStructure.............................. 19
2 Basic Concepts 21
	2.1 Web .................................... 21
		2.1.1 BrowserArchitecture....................... 22
		2.1.2 AudioandVideo ......................... 24
		2.1.3 CanvasElement.......................... 27
		2.1.4 JavaScriptTypedArrays..................... 28
	2.2 AugmentedReality ............................ 31
	2.3 Tracking.................................. 35
	2.4 MarkerlessTrackingTechniques ..................... 36
		2.4.1 ModelBased ........................... 36
		2.4.2 StructurefromMotion(SfM) .................. 40
3 Augmented Reality Library for the Web (tracking.js) 43
	3.1 Introduction................................ 43
		3.1.1 LibraryModules ......................... 44
	3.2 RelatedWork ............................... 47
	3.3 MarkerlessTrackingAlgorithm ..................... 51
	3.4 InterestPointDetection ......................... 51
	3.5 InterestPointDescriptionandMatching . . . . . . . . . . . . . . . . 52
	3.6 HomographyEstimation ......................... 56
	3.7 RandomSampleConsensus(RANSAC)................. 57
	3.8 PoseEstimation.............................. 58
	3.9 RapidObjectDetection(ViolaJones).................. 58
4 Evaluation 61
	4.1 Tools.................................... 61
	4.2 ScenarioDescription ........................... 61
	4.3 EvaluationMethodology ......................... 61
		4.3.1 MatchingRobustness....................... 61
		4.3.2 OclusionRobustness ....................... 61
		4.3.3 FPS ................................ 61
	4.4 Results................................... 61
5 Conclusion 63
	5.1 Contributions ............................... 63
	5.2 FutureWork................................ 63


// Changes ---------------------------------------------------------------------

2 Basic Concepts
	2.1 Web
		2.1.1 Contextualization
		2.1.2 Browser Architecture
		2.1.3 Audio and Video
		2.1.4 Canvas Element
		2.1.5 JavaScript Typed Arrays
	2.2 Visual Tracking
		2.2.1 Contextualization
		2.2.2 Tracking In Augmented Reality Applications
	2.3 Augmented Reality
		2.3.1 Contextualization
		2.3.2 What devices could use tracking.js?
	3 Tracking Library for the Web (tracking.js)
		3.1 Contextualization
			3.1.1 Related Work
			3.1.2 Library Modules
		3.3 Markerless Tracking Algorithm
			3.3.1 Contextualization
			3.3.2 Interest Point Detection
			3.3.3 Interest Point Description and Matching
			3.3.4 Homography Estimation
			3.3.5 Random Sample Consensus(RANSAC)
		3.4 Color Tracking
			3.4.1 Contextualization
		3.5 Rapid Object Detection (Viola Jones)
			3.5.1 Contextualization













--

CHAPTER 2 STATE OF THE ART AND RESEARCH DESIGN ............................................. 19
2.1 VISUAL TRACKING...................................................................................................................... 19
2.1.1 TRACKING IN AUGMENTED REALITY APPLICATIONS................................................................ 21
2.2 DECISION THEORY...................................................................................................................... 22 CHAPTER 3 STUDY OF EXISTING TRACKING APPROACHES ........................................ 24
3.1 DIFFERENT TRACKING APPROACHES ....................................................................................... 24
3.1.1 MEAN SHIFT .............................................................................................................................. 24
3.1.2 CAMSHIFT .................................................................................................................................. 25
3.1.3 KALMAN FILTER ........................................................................................................................ 25
3.1.4 PARTICLE FILTER....................................................................................................................... 26
3.1.5 HARMONY FILTER ..................................................................................................................... 27
3.1.6 OPTICAL FLOW ........................................................................................................................... 27
3.1.7 ESM........................................................................................................................................... 28
3.1.8 MUTUAL INFORMATION BASED TRACKER ................................................................................ 28
3.2 BEST ALGORITHM SELECTION .................................................................................................. 29
3.3 DISCUSSION ................................................................................................................................. 30