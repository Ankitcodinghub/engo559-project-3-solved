# engo559-project-3-solved
**TO GET THIS SOLUTION VISIT:** [ENGO559 Project 3 Solved](https://www.ankitcodinghub.com/product/engo559-the-arctic-ocean-is-covered-with-a-blanket-of-sea-ice-sea-ice-is-frozen-sea-water-thus-it-is-salty-however-as-sea-ice-ages-the-salt-drains-out-so-ice-that-is-more-than-two-years-old-h/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;122060&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ENGO559 Project 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
The Arctic Ocean is covered with a blanket of sea ice. Sea ice is frozen sea water, thus it is salty. However, as sea ice ages, the salt drains out, so ice that is more than two years old, has a low enough salt content to enable humans to melt and drink it. Sea ice is a critical component to global climate. Sea ice appears white and reflects about 80% of the solar radiation. In summer as the temperatures rise, sea ice starts to melt exposing the ocean surface, which absorbs about 90% of the solar radiation. This heats the ocean which accelerates the melting of sea ice. Low amounts of summer sea ice in the Arctic can change the global climate.

Sea ice is also in constant motion being pushed by both winds and ocean currents. The motion of sea ice moves new and old ice around the Arctic which helps maintain a constant cover. As the ice move it deforms and opens up “leads”, which are small areas of open ocean. These leads are important both to the ecosystem, and to climate, as there is intense heat exchange between the cold Arctic air and the warmer ocean over the leads. There are several governmental organizations in Canada and the USA that produce operational estimates of sea ice motion in the Arctic.

Choose two images from the sequence and estimate the motion of the sea ice pack between the days. This can be done in at least two ways: (i) area correlation (template matching) which some of you used in detecting the baseball in Project 1, and (ii) feature matching. Area matching can be performed by dividing the first image into a two dimensional grid of points, then estimating the motion of each small sub-image centred at each point in the grid. Or you can find features in the image and use the feature locations as the centre of the sub-image. The alternative is to perform feature detection (discussed in class), and match the features themselves. In either method, you will need to define a search neighbourhood in the second image based on the location of either the sub-image or feature in the first image, and only search for the sub-image or feature within this search neighbourhood. If you search over the entire image, you will get too many false matches. In addition the correlation coefficient will likely be quite low in some cases, so you will want to check the magnitude of the correlation and set a threshold. Then only show the vectors corresponding to correlations greater than the threshold. If you view the two images one after the other you can see that the motion field is fairly smooth. The motion of

1

neighbouring points does not differ too much in either magnitude or direction. This might be another quality control element of your algorithm.

There are a number of possible ways to graphically represent your results. The most common method is to present a graph that is the same dimension as the image, with a small arrow centred at each point at which you estimated the motion, with the magnitude and direction of the motion indicated by the length and orientation of the arrow. This is illustrated in figure 1. On the left is a regular grid of points with the motion represented as small arrows. Not all points are shown since some of the correlations were below a

threshold. On the right is the result of feature detection and matching, with the motion represented by small circles at the point and a line segment indicating the motion. In this case the first image is the background for the motion.

Think about how to assess the accuracy of your results. As in previous projects, we have no ground data with which to compare your results. Thus you must manually estimate the motion at a number of points around the ice field. This is an operation similar to image registration in ENGO 435, however in this case, you must write the pixel coordinates in image 1 and image 2, and calculate the motion vector for each pair. After collecting several manual estimates of motion, think of ways you can describe the accuracy of your automated results.

2

Figure 1: Results of sea ice motion detection displayed in two different ways. On the left the motion field is displayed in a graph showing the axes. The motion was estimated using a regular grid of locations, and is displayed using small arrows. Points that are not shown had correlations that were below a threshold. Points where there was no motion are displayed as dots. On the right, the motion was estimated by matching features. The location of each feature is a small circle, and the motion is displayed as a small line segment.

3
