<h1>Verilog based car parking system</h1>
<br>
<p>
This project implements a Car Parking System using Verilog and a Finite State Machine (FSM). The system uses entrance and exit sensors to manage vehicle access, verifies user input through a password system, and displays the status using LEDs and 7-segment displays. It can be simulated on FPGA or using Verilog simulation tools to demonstrate the control of parking access.
</p>
<h2> Features </h2>
 <ul>
        <li><strong>Entrance and Exit Sensors</strong>: Detects when a car enters or exits the parking lot.</li>
        <li><strong>Password Verification</strong>: Uses a two-digit password input for allowing or denying parking access.</li>
        <li><strong>LED Indicators</strong>: 
            <ul>
                <li>Green LED turns on when access is granted.</li>
                <li>Red LED turns on when access is denied or waiting for input.</li>
                <li>Blinking LEDs indicate different system states.</li>
            </ul>
        </li>
        <li><strong>7-Segment Display</strong>: Shows the status of the system during different states (e.g., waiting for password, wrong password, parking granted).</li>
        <li><strong>Finite State Machine (FSM)</strong>: Implements a Moore FSM to control the behavior of the system.</li>
        <li><strong>Idle State</strong>: System waits for a car to arrive (entrance sensor activation).</li>
        <li><strong>Password Waiting State</strong>: System prompts for a password and waits for correct input.</li>
        <li><strong>Right/Wrong Password States</strong>: Handles correct and incorrect password scenarios with different state transitions.</li>
        <li><strong>Stop State</strong>: Halts when both entrance and exit sensors are triggered.</li>
    </ul>
