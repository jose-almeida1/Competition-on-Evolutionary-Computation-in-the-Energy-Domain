# 2025 Competition on Evolutionary Computation in the Energy Domain: Summer Finals of the Risk-based Energy Scheduling

![CFPs2025-13](https://github.com/user-attachments/assets/178e6794-92d9-4719-8437-82747f8e37e8)

[IEEE CEC 2025](https://www.cec2025.org/) & [GECCO 2025](https://gecco-2025.sigevo.org/HomePage) (Joint competition)

June 08 – June 12 – Hangzhou, China (CEC 2025) | July 14 – July 18 – Málaga, Spain (GECCO 2025)

Organized by Polytechnic of Porto (ISEP)

**Polytechnic of Porto (ISEP):** José Almeida, Fernando Lezama, João Soares, Bruno Canizes, Filipe Sousa, Zita Vale

**Important: The use of the software platform is prohibited for purposes other than competition without a prior authorization of the organizing team.**

**Results Published:** (TBD)

## Registration

**The registration of participants is mandatory** and must be made online using the following form: [link](https://forms.gle/S5rVvgw7WwfKNr7k8).

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
- The organizers provide a framework, implemented in MATALAB© 2021a 64 bits, in which participants can easily test their algorithms (we also provide a hybrid-adaptive differential evolution algorithm implementation as an example). The guidelines include the necessary information to understand the problem, how the solutions are represented, and how the fitness function is evaluated. Also, we provide information on mathematical formulation regarding the objective function value and problem constraints. Those elements are common for all participants.
- A maximum number of “function evaluations” is considered for all algorithms. However, this year, the algorithms’ convergence properties, measured as the number of “functions evaluations”, are part of the evaluation criteria in the competition. Thus, participants should strive to obtain the lowest number of “function evaluations” as well.
In addition, 20 independent trials should be performed in the framework by each participant.

## How to submit an entry

- The winner will be the participant with the minimum ranking index in the proposed track, which is calculated as the sum of the normalized values of the average fitness value and the average number of function evaluations for the 20 trials. Possible outliers in the normalization will be handled by the winsorizing of the results.
- Each participant is kindly requested to put the text files corresponding to final results (see guideline document), as well as the implementation files (codes), obtained by using a specific optimizer, into a zipped folder named:
CEC2025_track1_AlgorithmName_ParticipantName.zip (e.g.)
CEC2025_track1_HyDE_Lezama.zip).

**The participants should submit the files to the registration form ([link](https://forms.gle/S5rVvgw7WwfKNr7k8)) by 1st June 2025 (anywhere on Earth).**

## Important Remarks

- Notice that submission of papers or assistance to CEC and GECCO by competition participants is not mandatory.
- You can submit a paper to the CEC-2025 Special Session on Computational Intelligence for Control and Optimization of Complex Energy Systems ([~~Submit it here~~](https://www.cec2025.org/index/page.html?id=1298)) – select Special Session: Computational Intelligence for Control and Optimization of Complex Energy Systems.
- You are also welcome to submit short descriptions of your algorithms and results as 2-page papers to be included in the GECCO Companion. **This is voluntary:** the submission deadline is **12th April 2025 (closed)**. [~~Submit it here~~](https://gecco-2025.sigevo.org/Call-for-Papers) (**Competition Entry Submissions**)

**IEEE CES PRIZE:**

We are glad to announce that our competition will offer an **IEEE Computational Intelligence Society (CIS) prize of a total of 1000 $:**

- **500 $** for the participant with the best rank,
- **300 $** for the second best,
- **200 $** for the third best.
Good luck, and stay tuned. Thanks!

Submit your results by **1st June 2025 (anywhere on Earth)
**

## Further related bibliography

- [1] F., Lezama, J. Soares, Z. Vale, J. Rueda, S. Rivera, & I. Elrich, 2017 IEEE Competition on modern heuristic optimizers for smart grid operation: Testbeds and results. Swarm and evolutionary computation, 44, 420-427, 2019
- [2] F. Lezama, J. Soares, P. Hernandez-Leal, M. Kaisers, T. Pinto, and Z. Vale, Local Energy Markets: Paving the Path Towards Fully Transactive Energy Systems, IEEE Transaction on Power Systems, IEEE (2018).
- [3] Joao Soares, Bruno Canizes, M. A. Fotouhi Gazvhini, Zita Vale, and G. K. Venayagamoorthy, “Two-stage Stochastic Model using Benders’ Decomposition for Large-scale Energy Resources Management in Smart grids,” IEEE Transactions on Industry Applications, 2017.
- [4] F. Lezama, J. Soares, E. Munoz de Cote, L. E. Sucar, and Z. Vale, “Differential Evolution Strategies for Large-Scale Energy Resource Management in Smart Grids,” in GECCO ’17: Genetic and Evolutionary Computation Conference Companion Proceedings, 2017. 
- [5] Joao Soares, Mohammad Ali Fotouhi Ghazvini, Marco Silva, Zita Vale, “Multi-dimensional signaling method for population-based metaheuristics: Solving the large-scale scheduling problem in smart grids”, Swarm and Evolutionary Computation, 2016.
- [6] Joao Soares, Hugo Morais, Tiago Sousa, Zita Vale, Pedro Faria, “Day-ahead resource scheduling including demand response for electric vehicles”, IEEE Transactions on Smart Grid 4 (1), 596-605, 2013.
- [7] F. Lezama, J. Soares, B. Canizes, Z. Vale, Z., Flexibility management model of home appliances to support DSO requests in smart grids. Sustainable Cities and Society, 55, 102048, 2020.

## Organizers

José Almeida, Fernando Lezama, João Soares, Bruno Canizes, Filipe Sousa, Zita Vale
 
If you have any questions kindly send mail to José Almeida (jorga@isep.ipp.pt)


![Screenshot_1](https://github.com/user-attachments/assets/9da62d14-a843-4051-a84e-58945399d2f0)

- [Activity of IEEE CIS Task Force 3 on Computational Intelligence in the Energy Domain](https://www.gecad.isep.ipp.pt/ci4energy/)
- [Intelligent Systems Subcommittee (ISS), part of IEEE PES TC Analytic Methods for Power Systems (AMPS)](https://site.ieee.org/pes-iss/)
- With the support of [IEEE CIS](https://cis.ieee.org/) (TBD prize) and [IEEE PES (WG on MHO)](https://site.ieee.org/psace-mho/)
