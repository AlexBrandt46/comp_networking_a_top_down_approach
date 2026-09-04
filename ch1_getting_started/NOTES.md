# Wireshark Lab: Getting Started v9.0

**Link to PDF:** [Wireshark Intro v9.0](https://www-net.cs.umass.edu/wireshark-labs/Wireshark_Intro_v9.0.pdf)

## Questions

1. Which of the following protocols are shown as appearing (i.e., are listed in the
Wireshark “protocol” column) in your trace file: TCP, QUIC, HTTP, DNS, UDP,
TLSv1.2?

    ---

2. How long did it take from when the HTTP GET message was sent until the HTTP OK reply was received?

    > By default, the value of the Time column in the packet-listing window is the amount of time, in seconds, since Wireshark tracing began.  
    > If you want to display the Time field in time-of-day format, select the Wireshark *View* pull down menu, then select *Time Display* Format, then select *Time-of-day*.

    ---

3. What is the Internet address of the gaia.cs.umass.edu (also known as `www-net.cs.umass.edu`)? What is the Internet address of your computer or (if you are
using the trace file) the computer that sent the HTTP GET message?

    ---

4. Expand the information on the HTTP message in the Wireshark “Details of selected packet” window (see Figure 3 above) so you can see the fields in the HTTP GET request message. What type of Web browser issued the HTTP request? The answer is shown at the right end of the information following the “User-Agent:” field in the expanded HTTP message display. [This field value in the HTTP message is how a web server learns what type of browser you are using.]

    • Firefox, Safari, Microsoft Internet Edge, Other

    ---

5. Expand the information on the Transmission Control Protocol for this packet in the Wireshark “Details of selected packet” window (see Figure 3 in the lab writeup) so you can see the fields in the TCP segment carrying the HTTP message. What is the destination port number (the number following “Dest Port:” for the TCP segment containing the HTTP request) to which this HTTP request is being sent?

    ---

6. Print the two HTTP messages (GET and OK) referred to in question 2 above. To do so, select *Print* from the Wireshark *File* command menu, and select the *“Selected Packet Only”* and *“Print as displayed”* radial buttons, and then click OK.
