Download Link: https://assignmentchef.com/product/solved-cs-3700-computer-networks-homework-7
<br>
<strong>Problem A</strong>. Consider a datagram network using 32-bit host addresses. Suppose a router has four links, numbered 0 through 3, and packets are to be forwarded to the link interfaces as follows:

Destination Address Range                                                                                                                    Link Interface

11100000 00000000 00000000 00000000 through 11100000 00111111 11111111 11111111                                            0

11100000 01000000 00000000 00000000 through 11100000 01000000 11111111 11111111                                            1

11100000 01000001 00000000 00000000 through 11100001 01111111 11111111 11111111                                            2

Otherwise                                                                                                               3

<ol>

 <li>Provide a <strong>forwarding table</strong> that has <strong>five entries</strong>, uses <strong><em>longest prefix matching</em></strong>, and forwards packets to the correct link interfaces.</li>

 <li>Describe how your forwarding table determines the appropriate link inter-face for datagrams with destination addresses:       11001000 10010001 01010001 01010101</li>

</ol>

11100001 01000000 11000011 00111100

11100001 10000000 00010001 01110111

(Hint: There is an example discussed in class and included in the in-class notes &amp; PPT slides for Chapter 4)







<strong>Problem B.</strong> Consider a datagram network using 8-bit host addresses. Suppose a router uses longest prefix matching and has the following forwarding table:

Prefix Match                                           Interface

1                                              0

10                                            1                                  111                                          2                                  otherwise                                3

For <strong>each of the four interfaces</strong>, give the <strong><em>associated range of destination host addresses</em></strong> and the <strong><em>number of addresses in the range</em></strong>.

<strong> </strong>

<strong> </strong>

<strong>Problem C.</strong> Consider sending a 2400-byte datagram into a link that has an MTU of 700 bytes. Suppose the original datagram is stamped with the identification number 422. How many fragments are generated? What are the values in the various fields in the IP datagram(s) generated related to fragmentation? (<strong>Hint</strong>: You may assume that the length of the IP header is 20 bytes.)







<strong>Problem D</strong>. Consider a router that interconnects three subnets: Subnet 1, Subnet 2, and Subnet 3. Suppose all of the interfaces in these subnets are required to have the prefix 134.39.176.0/22. Also suppose that Subnet 1 needs to support at least 450 interfaces, Subnet 2 needs to support at least 200 interfaces, and Subnet 3 needs to support at least 160 interfaces. Provide three network addresses (a.b.c.d/x) that satisfy these constraints.







<strong>Problem E</strong>. Rewrite the following forwarding table using the a.b.c.d/x notation:

Prefix Match                                                           Link Interface

11100000 00****** ******** ********                             0

<ul>

 <li>01000000 ******** ********                 1</li>

</ul>

1110000* ******** ******** ********                             2

<ul>

 <li>1******* ******** ********                 3</li>

</ul>




<strong> </strong>


