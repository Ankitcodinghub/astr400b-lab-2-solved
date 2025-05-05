# astr400b-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [ASTR400B Lab 2 Solved](https://www.ankitcodinghub.com/product/astr400b-lab-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;102229&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ASTR400B Lab  2  Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Make sure to have a cloned copy of your own repository on your computer (or nimoy if you are using nimoy for Jupyter). Create a directory Labs/Lab2.

From the command line git clone the class repository. If you have already done this, git pull to update the repository. There is a directory Labs/Lab2/ with a file Lab2.ipynb, which is the template for this exercise.

Copy this template to your own repository directory Labs/Lab2

2 Schechter Function

The galaxy luminosity function in the nearby universe is well described by a Schechter Function:

Φ(M)dM = (0.4 ln10) φ∗ 100.4(M∗−M)(α+1)e−100.4(M∗−M) dM (1) With the following parameters from Smith+2009 for Field Galaxies in SDSS at z∼0.1 in

the Kband:

1. φ∗ =1.66 ×10−2 h3 Mpc−3

2. α = -0.81

3. M∗ = M∗k= -23.19 – 5log(h)

h = the Hubble constant in units of 100 km/s/Mpc . At z=0 this is 0.7. But we are going to ignore it here. Units will then be in ”comoving” coordinates.

2.1 Question 1

Utilizing the defined function in the template file, plot the Schechter Function using the above parameter values over a magnitude range of -17 to -26. Try to reproduce the black solid line in Figure 2.1, from Smith+2009

Plotting tips:

1. import matplotlib.pyplot as plt – this lets you use plotting functions.

2. np.arange(0,10,0.1) will return an array from 0 to 10 spaced in intervals of 0.1 3. plt.semilogy lets you plot the y axis as log.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Figure 1: Luminosity Function from Smith+2009, UKIDSS + SDSS KBand

2.2 Question 2

Galaxies in the Virgo Cluster have different parameters, like α=-1.35 (Ferrarese+2016 ApJ 824) Overplot the Schechter Function with this new value of α. Try a smaller value of α = −0.6. How does the function change? What does this mean?

2.3 Question 3

Build a function to compute the Schechter Function in terms of luminosity.

Use ‘quad‘ to determine the fraction of the luminosity that lies above L* in the following

three cases: α=-0.7 (default), α=-0.6, α=1.85. Schechter Function:

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
<div class="column">
n∗ = 0.008 h3 Mpc−3 L⋆ = 1.4 × 1010L⊙

The IMF

</div>
</div>
<div class="layoutArea">
<div class="column">
n∗ 􏰀 L 􏰁α

Φ(L) = L L e−L/L∗ (2)

∗∗

</div>
</div>
<div class="layoutArea">
<div class="column">
Create a function called Salpeter that defines the Salpeter IMF:

ξ(M) = ξ0(M/M⊙)−α (3)

α = 2.35 The function should take as input an array of stellar masses, M. You will need to determine the normalization, ξ0, by integrating this equation over mass from 0.1 to 120 M⊙

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
and setting the value to 1. The function should then return ξ(M), which will now represent the fractional number of stars.

• from scipy.integrate import quad

• quad(lambda x: fxn(x),xmin,xmax)

• quad returns an array with 2 values. you want the first value.

3.1 Question 1

Integrate your normalized function to compute the fraction of stars with stellar masses greater than the sun and less than 120 M⊙. ** Double Check: if you integrate your function from 0.1 to 120 you should return 1.0

3.2 Question 2

How might you modify the above to return the fraction of mass in stars more massive than the Sun?

4 Last Step

Git push your Lab1.ipynb file to your repo. Recall steps: 1. git add filename

2. git commit -m ”COMMENTS”

3. git push

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
