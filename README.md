# Stochastic-simulation-project

An implementation of the paper: J. Huang et al. (2015) "Control of Patient Flow in Emergency Departments, or Multiclass Queues with Deadlines and Feedback". Operations Research 63(4):892-908. https://doi.org/10.1287/opre.2015.1389. This implementation is also part of a project done for a grad level course in Winter 2020. 


In a hospital, the control of the patient flow can have a significant impact on its operational performance and the quality of care the patients received. 
The ultimate goal is to meet the patient’s demand within a reasonable time. 
The problem considered in this project is the patient flow control in the emergency department (ED) where certain deadlines should be met for the patient’s first visit to the physician, 
and the patient may return multiple times after the first visit.

The paper (Huang et al. 2015) proposed a threshold policy to improve the operational performance of the ED. 
In this project, I used the discrete-event simulation to model the process, 
and the queueing model as well as the policy described in the paper was implemented, analyzed, and compared with a general first-come-first-served policy.

The jupyter notebook also included my experiment design process in which the warm-up period and number of replications were determined.

The model implementation used the PythonSim package.
