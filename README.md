# cs3357a-assignment-2--chatroom-applications-using-tcp-and-udp-solved
**TO GET THIS SOLUTION VISIT:** [CS3357A Assignment #2- Chatroom Applications Using TCP and UDP Solved](https://www.ankitcodinghub.com/product/cs3357a-assignment-2-building-two-chatroom-applications-using-tcp-and-udp-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119623&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3357A Assignment #2- Chatroom Applications Using TCP and UDP Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. Assignment Purpose:

The purpose of this assignment is to expand on your network/socket programming skills by building a chatroom application that uses both TCP and UDP protocols. Additionally, you’ll analyze network traffic using Wireshark. No need to implement GUI,

2. Assignment Description:

You will develop two versions of the chatroom application: one using TCP and the other using UDP. Each version should have the following features:

2.1.Common Features (Both TCP and UDP):

• Accept multiple client connections.

• Allow clients to send messages to the server.

• Broadcast messages from one client to all other connected clients.

• Handle client disconnections gracefully (without crashing the server).

2.2.TCP Version:

• Use TCP for communication between the server and clients.

• Implement the code in the provided template files: tcp_server.py for the server and tcp_client.py for the client.

2.3.UDP Version:

• Utilize UDP for communication between the server and clients.

• Implement the code using the provided template files: udp_server.py for the server and udp_client.py for the client.

• Ensure that the server can correctly identify the source client of each received message in the UDP protocol.

In Wireshark software, capture network traffic while running TCP (running `tcp_server.py` &amp; `tcp_client.py`) and UDP (`udp_server.py` &amp; `udp_client.py`) versions of your chatroom application. You should capture packets sent and received during chatroom interactions. Then analyze the captured packets using Wireshark to understand the differences between TCP and UDP in terms of packet structure, parameters and other relevant network characteristics.

3. Resources Requirements:

• Install Python and the necessary Python package manager (e.g., Anaconda or pip).

• Install Wireshark software (https://www.wireshark.org/)

• Download the provided GitHub repository (www.github.com/eyadgad/CS3357_A2), which contains template files for both the TCP and UDP versions of the chatroom application.

4. Rubric:

5. Successfully Done Coding!! Let’s Test:

1. Open Wireshark and select the “loopback traffic capture” interface for packet capture.

2. Open multiple windows (e.g., 3) for executing the Python files.

3. Run tcp_server.py in one window and verify that the server is ready to accept connections.

4. In the other windows, run tcp_client.py &lt;username&gt; and confirm successful connections.

5. Check that the server received their usernames and printed them upon connection.

6. Send messages from any client window and verify if they are received by the server and other clients.

7. In Wireshark, select the message packet from the traffic, check the data or parameters from the lower-left window, and save the analysis as a backup file. Quit packet capturing.

8. Repeat the above steps, but this time with the UDP chatroom application.

9. After testing UDP, collect the data from the traffic, compare it with the TCP packet analysis and describe what you understood from the comparison.

10. Prepare all required deliverables and proceed with the submission of your assignment.

See a demo video of my testing in UDP version.

6. Deliverables:

For this assignment submission, prepare a compressed directory named “lastname_studentID” containing the following five files:

1. lastname_studentID.pdf: This PDF file should include the followings:

a. Student name, ID, and email address.

b. Chatroom section: record one quick video (screen share) to test the chatroom application for TCP and UDP (must show the server and two or more clients windows, and simple conversation in the chatroom).

c. Wireshark section: include the following components:

▪ Analysis description: two or more sentences concluding the analysis or describing the comparison between TCP and UDP. (e.g., what are the different or similar parameters in both versions)

▪ Images: Integrate two screenshots (one for TCP and one for UDP) from Wireshark to support your analysis description.

2. tcp_server.py: This Python file should contain the code for the TCP server.

3. tcp_client.py: This Python file should contain the code for the TCP client.

4. udp_server.py: This Python file should contain the code for the UDP server.

5. udp_client.py: This Python file should contain the code for the UDP client.

Ensure that these files are organized within the “lastname_studentID” directory and then compress the entire directory into a single compressed file (e.g., a ZIP or TAR file) for submission.

8. Struggling!! Let’s Meet:

Feel free to seek assistance during any consultancy hours. However, for implementation issues, I recommend the following hours:

o Gad Gad, Mon 12:00 – 02:00, https://westernuniversity.zoom.us/j/94758934201 Pass:347367 o Eyad Gad, Fri 11:00 – 01:00, https://westernuniversity.zoom.us/j/92072575085 Pass: 3357

Not available during these hours or need immediate help? reach out to me

Enjoy coding,

Eyad Gad egad@uwo.ca
