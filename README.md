# cs232-assignment-7-solved
**TO GET THIS SOLUTION VISIT:** [CS232 Assignment 7 Solved](https://www.ankitcodinghub.com/product/cs232-assignment-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121075&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS232 Assignment 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Description of design:

There is a traffic junction with five lanes L0, L1, L2, L3 &amp; L4. Among these, L1 &amp; L4 are small side lanes with light traffic, and the rest are highways with heavy traffic. To control the traffic, placed at the centre of the junction is a single traffic signal lights pole which has 15 lights – 3 for each lane – red, green and yellow. You need to design a digital circuit called a traffic lights controller to control these 15 lights. The controller has 15 output wires connected to each of the lights. The controller turns on a particular light by sending a logic ‘1’ on the corresponding wire and turns off the same by sending a logic ‘0’.

At a time only one lane should be given a green signal, and during that time, the rest of the lanes should be given a red. After a green on a particular lane, yellow should be given on the same lane for a short while, after which it turns red, and simultaneously the next lane will be made green. The green signal duration for the smaller lanes (L1 &amp; L4) is 30 seconds. For the rest of the lanes, which are highways, it is 60 seconds. Also on the smaller lanes, some sensors are placed which will try to detect the traffic. If there is no one waiting on the smaller lanes then they will not be given green and skipped to the next lane. If there is at least one person on the lighter lane, only then it will be given a green for 30 seconds. The yellow signal duration is 5 seconds for all the lanes. As soon as the traffic lights controller is powered on (which is the same as making the reset input of the circuit high for one clock cycle), L2 should be given a green followed by L3, L4, L0 and L1. After L1, the pattern repeats again from L2, and it keeps going on infinitely. The entity statement is given below, and the purpose of the outputs is intuitive. ‘tr1’ and ‘tr4’ inputs are coming from the sensors placed on the smaller lanes. If ‘tr1’ is logic ‘1’, then it means there is some traffic on lane L1. If it is ‘0’ then it means there is no one on lane L1 and it is completely free. Similarly ‘tr4’ is for lane L4. The clock frequency should be fixed, and it should not vary during the operation of the circuit.

entity TrafficLightsController is

port ( clk, rst, tr1, tr4 : in std_logic; r, g, y: out std_logic_vector (4 downto 0) );

end entity;

Things required in Submission:

1. All VHDL files of top-level and sub-components and also the testbench (.vhd or .vhdl files).

2. Screenshot of Waveforms (Few input patterns are sufficient).

3. A report explaining how you designed (pdf format).

Submission rules:

2. Create a folder named lab7 (all small letters and no spaces).

3. Inside the folder, put all the .vhd or .vhdl files of both top-level entity and sub-components. Also, in the same folder, put the related waveform screenshots and the pdf report.

4. Finally, before you submit the lab7 folder on moodle, you will be zipping it. The zip file should have your id number as the name. For eg: if your id is 184070026 then your zip file will be 184070026.zip.
