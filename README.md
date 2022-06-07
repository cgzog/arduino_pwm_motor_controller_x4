# arduino_pwm_motor_controller_x4
Control up to 4 FRC PWM motor controllers for testing

Hardware-wise you want some conventional linear taper potentiometers (10k is fine but the value is not critical)
and some center off SPDT or DPDT switches (you only need one pole but DPDT center offs are easier to find).
You can easily work out the wiring from the Arduino project (one analog input, one PWM output, and two directional control pins per motor).
