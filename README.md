# RL_in_ksp

This repo is in development. The following is planned:
1) Solution using sb3.ppo (this has already been successfully attempted)
2) Solution using only pytorch, no sb3 (this is in development)


########################################################
1) Install requirements:<br />
`pipenv install`

2) Add project src folder to PYTHONPATH:<br />
`export PYTHONPATH="${PYTHONPATH}:$(pwd)/src"`

3) 
- Start no ML no PID simulation: <br />
`python src/engineering_approach/no_pid.py` 
Telemetry plots are saved in `src/engineering_approach/plots`

- Start no ML simulation with PID used for rcs:<br />
`python src/engineering_approach/rcs_pid.py` 

- Generate random train data for rewards:<br />
`python src/RL/generate_train.py` 
