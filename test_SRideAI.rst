
Testing SRIDE AI
=================

.. raw:: html

    <h2>Testing SRIDE AI</h2>

    <h3>Purpose:</h3>
    <p>The SRIDE AI system is designed to monitor and evaluate the behavior of robots during autonomous missions. By leveraging human neuroscience-inspired AI algorithms, it offers insights into the mission's health, ensuring optimal performance and highlighting potential issues.</p>

    <h3>How to Use SRIDE AI:</h3>
    <ol>
        <li>
            <strong>Select Your Robot:</strong>
            <p>Click on the <button id="ChooseRobot">Choose Robot</button> button.</p>
        </li>
        <li>
            <strong>Specify the Mission:</strong>
            <p>Choose the desired mission by clicking on the <button id="ChooseMission">Select Mission</button> button.</p>
        </li>
        <li>
            <strong>Upload Mission Data:</strong>
            <p>For instance, if you're evaluating the <em>scantest</em> mission on day 32, upload the mission data file for that day.</p>
            <p><input id="fileInput" type="file" /></p>
        </li>
        <li>
            <strong>Analyze the Data:</strong>
            <p>Press the <button id="submitButton">Process Data</button> button. SRIDE AI will then analyze the mission's execution, comparing it against the robot's standard behavior for that specific mission.</p>
        </li>
    </ol>

    <h3>Results Interpretation:</h3>
    <p>After processing, SRIDE AI will provide a quantified result indicating the mission's health. For example, you might receive a result stating there's a "4% chance of anomalous presence." This critical information allows manufacturers or users to proactively address and debug potential issues.</p>

    <h3>Benefits:</h3>
    <p>By identifying any anomalies in the robot's behavior during a mission, users can ensure consistent performance, enhance the robot's longevity, and avoid potential pitfalls.</p>
