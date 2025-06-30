Forensic Artifact Parser & Analyzer (FAPA)


⟩ Overview
FAPA is a Python-based tool crafted to aid digital forensic analysts in processing and interpreting custom log files generated from simulated or non-standard operating systems. Designed with flexibility and clarity in mind, this utility transforms raw, unstructured logs into meaningful insights—supporting investigations through event tracing, anomaly detection, and visual reporting.


⟩ Why Log Analysis Matters in Digital Forensics

Log files act as the digital memory of a system, capturing activities over time. Analyzing these logs is a cornerstone of forensic work due to its ability to:

» Recreate System Activity: Understand what happened, when, and by whom—whether it’s a file access, login attempt, or program launch.

» Spot Unusual Behavior: Detect unauthorized access, suspicious executions, or data manipulation by analyzing inconsistencies.

» Support Legal Investigations: Provide timestamped, tamper-evident records useful as supporting evidence.

»Assign Responsibility: Link actions to users or system components for accountability.

»Respond to Incidents: Inform response strategies and strengthen security post-breach. 


⟩ Key Features

» Flexible Log Parsing: Capable of handling custom log formats and extracting structured data.

» Event Grouping: Automatically tags different types of system events (user actions, file changes, processes).

» Anomaly Detection Engine: Highlights events that deviate from expected behavior.

» Event Timeline Builder: Constructs an ordered sequence of system events for investigation.

» Data Visualization: Generates charts and visual reports to simplify data interpretation. 


⟩ Built With
» Python 3
» Pandas – for data manipulation
» Matplotlib & Plotly – for graphing and charts
» argparse – for command-line input handling
» Custom Rule Engine – for pattern-based anomaly detection

⟩ Academic Note : This tool was developed as part of the Digital Forensics and Information Security (DFIS) academic program. It is intended solely for learning, experimentation, and research purposes—not for commercial or real-world forensic applications.
