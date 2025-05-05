# CPE 322-Lab 7
## ThingSpeak and Google Sheets

---

### Part 1: ThingSpeak
The initial part of the lab involved using ThingSpeak, MathWorks’ cloud-based data analysis platform, to collect and visualize system CPU and memory usage data. An existing MathWorks account, previously used with MATLAB, was used to log into ThingSpeak. A new channel named cpu_loop was created, featuring two fields: cpu_data for logging CPU usage percentage and mem_avail_mb for tracking available memory in megabytes.

![Half Adder](halfadder.png)

The necessary Python files, thingspeak_cpu_loop.py and thingspeak_feed.py, were placed in a demo folder. The thingspeak_feed.py script was then executed using Python. Upon launch, the program prompted for a ThingSpeak API key, which was copied from the ThingSpeak website, entered into the provided text field, and saved. Once configured, the script began printing and uploading system CPU and memory data to the ThingSpeak server, where the data was visualized in real time on two separate graphs.

![Half Adder](halfadder.png)

![Half Adder](halfadder.png)
