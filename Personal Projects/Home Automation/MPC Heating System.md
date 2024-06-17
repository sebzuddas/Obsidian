Current home automation systems fall short in their control approaches, using mostly event-based control. This approach has many flaws. 

MPC seems like an appropriate technique to attempt a more sophisticated home automation system, leveraging the power of HAOS as the 'single source of truth' for a given building.

The idea is that you have an MPC for a given room, perfect that, then each subsequent room also has an MPC, that should be able to be replicated. Then, you use distributed MPC as an approach to control parameters across the building. The central controller then should be able to go between controlling individual rooms to controlling the whole building. 

https://web.casadi.org/ - For crating non-linear mpc


# Sampling Data from [[TimescaleDB]]

At present, it seems as though the ltss table within the timescaleDB only samples sensors when they have a changing state. This presents an issue with creating data-driven models, since the data only shows their performance during their on state. To address this, it is possible to resample data in [[Python Pandas]], using the `resample`



