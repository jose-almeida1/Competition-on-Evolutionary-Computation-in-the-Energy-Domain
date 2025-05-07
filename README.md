# Competition-on-Evolutionary-Computation-in-the-Energy-Domain
![CFPs2025-13](https://github.com/user-attachments/assets/178e6794-92d9-4719-8437-82747f8e37e8)

IEEE CEC 2025 & GECCO 2025 (Joint competition)

June 08 – June 12 – Hangzhou, China (CEC 2025) | July 14 – July 18 – Málaga, Spain (GECCO 2025)

Organized by Polytechnic of Porto (ISEP)

Polytechnic of Porto (ISEP): José Almeida, Fernando Lezama, João Soares, Bruno Canizes, Filipe Sousa, Zita Vale

Important: The use of the software platform is prohibited for purposes other than competition without a prior authorization of the organizing team.

Results Published: (TBD)

## Registration

The registration of participants is mandatory and must be made online using the following form: [link] (https://forms.gle/S5rVvgw7WwfKNr7k8).

Note: If you are unable to complete this form, please send it by email to: jorga@isep; jan@isep.ipp.pt; flz@isep.ipp.pt; bmc@isep.ipp.pt; ffeso@isep.ipp.pt; zav@isep.ipp.pt

## Final Rank Results

(TBD)

## Competition Outline

Following the success of the previous editions at IEEE PES-GM, CEC, GECCO, and WCCI, we are launching another challenging edition of the competition at major conferences in the field of computational intelligence and power systems. This CEC and GECCO 2025 competition proposes one track in the energy domain associated with the risk-based optimization of aggregators’ day-ahead energy resource management (ERM), considering uncertainty associated with the high penetration of distributed energy resources (DER). This testbed is constructed under the same framework of past competitions (therefore, former competitors can adapt their algorithms to this new track), representing a centralized day-ahead ERM in a smart grid with a 13-bus distribution network using a 15-scenario case study with 3 scenarios considering extreme events (high impact, and low probability). A conditional value-at-risk (CVaR) mechanism measures the risk associated with extreme events for a confidence level (α) of 95%. We also add some restrictions to the way in which initial solutions are generated. Finally, as in previous editions, manual repairs in the variables and tweak heuristics are not allowed.

Note: The track is developed to run under the same framework as past competitions.

## Competition goals

The competition has been held since 2017 at major conferences (the first competition was launched at IEEE PES GM) – Website: http://www.gecad.isep.ipp.pt/smartgridcompetitions.

We have been implementing some variants in the benchmark problems but have always been using the same framework. This year, we recover the 2023 track related to energy resource management, considering risk measurement tools (a more recent problem in the energy domain), but using a new evaluation criteria including the fitness value and the number of function evaluations (e.g., convergence).

## Rules

- Participants will propose and implement metaheuristic algorithms (e.g., evolutionary algorithms, swarm intelligence, estimation of distribution algorithm, etc.) to solve the proposed track problem in the energy domain.
- The organizers provide a framework (Download), implemented in MATALAB© 2021a 64 bits, in which participants can easily test their algorithms (we also provide a hybrid-adaptive differential evolution algorithm implementation as an example). The guidelines (Download) include the necessary information to understand the problem, how the solutions are represented, and how the fitness function is evaluated. Also, we provide information on mathematical formulation regarding the objective function value and problem constraints. Those elements are common for all participants.
- A maximum number of “function evaluations” is considered for all algorithms. However, this year, the algorithms’ convergence properties, measured as the number of “functions evaluations”, are part of the evaluation criteria in the competition. Thus, participants should strive to obtain the lowest number of “function evaluations” as well.
In addition, 20 independent trials should be performed in the framework by each participant.
