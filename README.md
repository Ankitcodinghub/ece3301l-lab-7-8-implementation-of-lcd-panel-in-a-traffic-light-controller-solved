# ece3301l-lab-7-8-implementation-of-lcd-panel-in-a-traffic-light-controller-solved
**TO GET THIS SOLUTION VISIT:** [ECE3301L LAB 7 & 8-Implementation of LCD Panel in a Traffic Light Controller Solved](https://www.ankitcodinghub.com/product/ece3301l-lab-7-8-implementation-of-lcd-panel-in-a-traffic-light-controller-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91491&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE3301L LAB 7 \u0026amp; 8-Implementation of LCD Panel in a Traffic Light Controller Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
LAB 7: Implementation of LCD Panel in a Traffic Light Controller

We will use the traffic light control system designed on Lab #7 that has the following hardware:

<ol>
<li>1) &nbsp;4 sets of RGB LEDs with the following assignments:

a. 1 RGB LED for North/South direction

b. 1 RGB LED for North/South Left Turn direction c. 1 RGB LED for East/West direction

d. 1 RGB LED for East/West Left Turn direction</li>
<li>2) &nbsp;Four DIP switches used as sensors with the following designations:
<ol>
<li>NS Switch Pedestrian (NSPED_SW) switch acting to indicate pedestrian present in the North/South direction</li>
<li>NS Left Turn (NSLT_SW) switch acting as a sensor for cars making left turn on the North/South direction</li>
<li>EW Switch Pedestrian (EWPED_SW) switch acting to indicate pedestrian present in the East/West direction</li>
<li>EW Left Turn (EWLT_SW) switch acting as a sensor for cars making left turn on the East/West direction</li>
</ol>
</li>
<li>3) &nbsp;Light Sensor to define the mode of operation. There will be two modes: Day Mode and Night Mode.</li>
<li>4) &nbsp;A MODE LED to indicate the mode the traffic controller is running (0 for Night and 1 for Day)</li>
<li>5) &nbsp;A SEC_LED to show 1 second pulse</li>
<li>6) &nbsp;Two 7-segment LEDs used to show the number of seconds for pedestrian crossings for each direction</li>
<li>7) &nbsp;A Buzzer circuit</li>
</ol>
From that circuit, we are going to modify to a new circuit that will have the following:

1) Instead of the two 7-segment displays, a LCD TFT Display is used to show the operation of the controller. A typical screen shot is shown below:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2) Some of the RGB LEDs will have new connections but their functions remain the same (see attached schematics for new pin assignments).

Here are some descriptions on the information on the above TFT screen:

<ol>
<li>1) &nbsp;First Line: Name of this class and its semester</li>
<li>2) &nbsp;Mode: Actual mode the controller is running – A ‘D’ will indicate the day mode while a ‘N’ will specify the night mode.</li>
<li>3) &nbsp;FR and FS fields: These will be defined on Lab #8. Ignore for now.</li>
<li>4) &nbsp;‘NORTH/SOUTH’: The box below this line shows the color of the traffic light in the North/South direction. There are three circles below this box each with the color Red, Yellow, and Green from left to right. When the circle is not filled, this means that the light is off. When it is filled, the corresponding color is on.</li>
<li>5) &nbsp;The two ‘00’ digits at the right of the ‘NORTH/SOUTH’ are used to display the number of seconds left on this direction when the lights are turned into the green and yellow colors.</li>
<li>6) &nbsp;There are three other labels ‘N/S LT’, ‘EAST/WEST’, ‘E/W LT’. They have the same descriptions as for the North/South direction but each item is for a different direction.</li>
<li>7) &nbsp;The label ‘PNS’ and the number right below it show the actual number of seconds left on the Pedestrian Counter in the North/South direction.</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="8">
<li>8) &nbsp;The label ‘PEW’ and the number right below it show the actual number of seconds left on the Pedestrian Counter in the East/West direction.</li>
<li>9) &nbsp;The line at the bottom shows the following: ’ NSP NSLT EWP EWLT MD’. The numbers below that line show the status of the switches for the North/South PED, NSLT, East/West PED, EWLT sensors and the logic state of the light sensor for MODE (This is the instant sensing of the light sensor and not the actual mode of operation).</li>
</ol>
The operation of the traffic light was already implemented on Lab #6.

The TFT Panel uses the hardware interface called SPI Bus in order for the microcontroller to control the panel to display data on its screen. The basic understanding of the SPI bus will be visited on a later lab and the hardware explanation will be handled at that time.

In addition, since it would take a good amount of time to implement all the software routines in order to allow the user to display texts or to generate different types of shapes, a library software has been compiled and put together into the file “ST7735_TFT.c”. This file should be included at the beginning of the ‘.c’ program to provide all library functions used in the program.

To develop the basic screen shown on the above screenshot, it will take a good amount of time to do so. We will skip this step. A basic routine is provided to the student that will create the basic framework of the screen. The student should look at the provided routine ‘Initialize_TFT()’ to get the basic ideas to implement the rest of the requirements of this lab.

Here are the definitions for the various values that the variable ‘direction’ can have:

</div>
</div>
<div class="layoutArea">
<div class="column">
#define NS 0 #define NSLT 1 #define EW 2 #define EWLT 3

</div>
<div class="column">
// Number definition of North/South

// Number definition of North/South Left Turn // Number definition of East/West

// Number definition of East/West Left Turn

</div>
</div>
<div class="layoutArea">
<div class="column">
Here are the definitions for the various values that the variable ‘color’ can have:

</div>
</div>
<div class="layoutArea">
<div class="column">
#define Color_Off 0 #define Color_Red 1 #define Color_Green 2 #define Color_Yellow 3

</div>
<div class="column">
// Number definition of Off Color // Number definition of Red Color

// Number definition of Green Color // Number definition of Yellow Color

</div>
</div>
<div class="layoutArea">
<div class="column">
We will need to implement the codes for the following functions: A) voidupdate_LCD_color(chardirection,charcolor)

This routine will change the color of the traffic light on the TFT panel for the specified ‘direction’ with the specified ‘Color’. Fox example, if this function is called with direction=NS and

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
.

</div>
<div class="column">
Color=Color_Red, then the RED light in the North/South field should be filled. The other two colors (Yellow and Green) should have only its outline drawn but inside the circle should not be filled.

Here is a portion of that routine providing a starting example:

void update_LCD_color (char direction, char color) {

char Circle_Y;

Circle_Y = NS_Cir_Y + direction * 30;

if (color == Color_Off) //if Color off make all circles black but leave outline {

fillCircle(XRED, Circle_Y, Circle_Size, ST7735_BLACK); fillCircle(XYEL, Circle_Y, Circle_Size, ST7735_BLACK); fillCircle(XGRN, Circle_Y, Circle_Size, ST7735_BLACK); drawCircle(XRED, Circle_Y, Circle_Size, ST7735_RED); drawCircle(XYEL, Circle_Y, Circle_Size, ST7735_YELLOW); drawCircle(XGRN, Circle_Y, Circle_Size, ST7735_GREEN);

}

// Add code for the remaining colors }

B) void update_LCD_count(char direction, char count)

This routine will change the value of the Second Counter (right side of the traffic light) for the specified ’direction’ with the value indicated by ‘count’.

Below is a beginning example of the routine:

void update_LCD_count(char direction, char count) {

</div>
</div>
<div class="layoutArea">
<div class="column">
}

</div>
</div>
<div class="layoutArea">
<div class="column">
switch (direction) // update traffic light no ped time {

case NS:

NS_Count[0] = count/10 + ‘0’;

NS_Count[1] = count%10 + ‘0’;

drawtext(XCNT, NS_Count_Y, NS_Count, NS_Color, ST7735_BLACK, TS_2); break; // Add code for the remaining directions

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
C) void update_LCD_PED_Count(char direction, char count)

This routine will change the value of the Pedestrian Counter (left side of the traffic light) for the specified ’direction’ with the value indicated by ‘count’.

Below is a beginning example of the routine:

void update_LCD_PED_Count(char direction, char count) {

switch (direction)

{

case NS:

PED_NS_Count[0] = count/10 + ‘0’;

PED_NS_Count[1] = count%10 + ‘0’;

drawtext(PED_Count_X, PED_NS_Count_Y, PED_NS_Count, NS_Color,

ST7735_BLACK, TS_2); //Put counter digit on screen break;

// Add code for the remaining direction

}

D) voidupdate_LCD_misc()

This routine will update the various states of the switches and the photo sensor. Below is an example of that routine:

</div>
</div>
<div class="layoutArea">
<div class="column">
void update_misc() {

char ch=0;

ADCON0 = ch*4+1;

int nStep = get_full_ADC(); volt = nStep * 5 /1024.0;

SW_MODE = volt &lt; 3.3 ? 1:0; SW_EWPED = EW_PED_SW; SW_EWLT = EW_LT_SW; SW_NSPED = NS_PED_SW; SW_NSLT = NS_LT_SW;

</div>
<div class="column">
// channel AN0

// calculates the # of steps for analog conversion

// gets the voltage in Volts, using 5V as reference

// SW_MODE = 1, Day_mode, SW_MODE = 0 Night

</div>
</div>
<div class="layoutArea">
<div class="column">
if (SW_MODE == 0) SW_MODE_Txt[0]= ‘N’; else SW_MODE_Txt[0] = ‘D’; // put code here to fill the fields for:

</div>
</div>
<div class="layoutArea">
<div class="column">
// PED count upper digit // PED Lower

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
// // // //

</div>
<div class="column">
SW_EWPED_Txt[0] &lt;- use ‘0’ if the switch is 0 and ‘1’ is the switch is 1 SW_EWL T_Txt[0]

SW_NSPED_Txt[0]

SW_NSL T_Txt[0]

</div>
</div>
<div class="layoutArea">
<div class="column">
drawtext(35,10, Act_Mode_Txt, ST7735_WHITE, ST7735_BLACK, TS_1);

drawtext(6, Switch_Txt_Y+9, SW_EWPED_Txt, ST7735_WHITE, ST7735_BLACK, TS_1); drawtext(32, Switch_Txt_Y+9, SW_EWLT_Txt, ST7735_WHITE, ST7735_BLACK, TS_1);

drawtext(58, Switch_Txt_Y+9, SW_NSPED_Txt, ST7735_WHITE, ST7735_BLACK, TS_1); drawtext(87, Switch_Txt_Y+9, SW_NSLT_Txt, ST7735_WHITE, ST7735_BLACK, TS_1); drawtext(112, Switch_Txt_Y+9, SW_MODE_Txt, ST7735_WHITE, ST7735_BLACK, TS_1);

}

E) When complete doing the creations of the new routines, perform the following modifications:

a. In the ‘void Set_NS(char color)’ routine, add at the beginning of the routine the following

lines:

direction = NS; update_color(direction, color);

b. repeat the same modifications for the other routines Set_NSLT(), Set_EW() and Set_EWL T()

c. In the ‘PED_Control(char direction, char count)’ routine, remove all the instructions to output to the PORTC and PORTD and replace them with the use of the newly created routine ‘void update_PED_Count(char direction, char count)’. Note, the value of the direction for NS is now 0 while for EW it becomes 2 and not 1 as in lab #7.

d. In the ‘void Wait_N_Seconds (char seconds)’ routine, replace with the following:

void Wait_N_Seconds (char seconds) {

char I;

for (I = seconds; I&gt; 0; I–) {

Wait_One_Second(); // calls Wait_One_Second for x number of times

update_LCD_count(direction, I); }

update_LCD_count(direction, 0);}

</div>
</div>
</div>
