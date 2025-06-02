![alt text](image.png)

What you need to solve :
- Basic concept wireshark
- Basic concept of networks

---

Starting off the challenge we were given a pcap file, we can open this file inside of wireshark.

In some of the packets there was a base64 data.

![alt text](image-1.png)

When we compare it to a normal data

![alt text](image-2.png)

As you can see the base64 seems to be appended?
So we can just filter out the length and gain 3 base64 strings

![alt text](image-3.png)

![alt text](image-4.png)

Flag : CSC{th1s_1s_w1r3shark_rawrrrrrrrrr}