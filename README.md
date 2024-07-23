Placeholder README for Green Energy Ship performance predictor.  Both better documentation and a better app are in work!

To try out the app, clone this repo into a folder on your MATLAB path, open the app in App Designer, and run from there.  It should find the Simulink model in the same directory.  The initial configuration will run the model with F-27 and Watt & Sea parameters to convergence.  Currently all of the parameters you can modify are independent, so there is no sanity check on, for example, whether your drag coefficient is at all appropriate for your wetted area.  You can reset the boat and turbine parameters to the known model using the dropdown menus.  

To match the tested configuration in the reference paper, set the wind speed to 5.14 m/s.  You can vary the turbine efficiency (eta) to approximate the power output of their prediction or the measured output.
