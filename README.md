# cs463-516-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS463-516 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs463-516-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95791&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS463-516 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Topics: Basic numpy, medical imaging modalities, SNR, and denoising

In this assignment we will familiarize ourselves with basic numpy array manipulation, different imaging modalities, and gain understanding of some basic image features (contrast and SNR).

Setup

First, install spyder (or any python IDE). If you are on windows, you will probably want to install anaconda first: https://docs.anaconda.com/anaconda/install/

• Note – you don’t need to use spyder (any python IDE is fine) but it will help a lot in this course because the attached console is very useful for debugging and visualization of intermediate results.

Second, get the images (link below). This directory contains 6 images:

https://drive.google.com/file/d/15O0f9T2tadF7WK2uFrLT7SLG46vpHyNN/view?usp=sharing

SWI (susceptibility weighted image): sub-01_ses-forrestgump_anat_sub-01_ses-forrestgump_acq-mag_veno.nii.gz

TOF (time of flight): sub-01_ses-forrestgump_anat_sub-01_ses-forrestgump_angio.nii.gz

T1 (T1-weighted image): sub-01_ses-forrestgump_anat_sub-01_ses-forrestgump_T1w.nii.gz

T2 (T2-weighted image): sub-01_ses-forrestgump_anat_sub-01_ses-forrestgump_T2w.nii.gz

DWI (Diffusion weighted image): sub-01_ses-forrestgump_dwi_sub-01_ses-forrestgump_dwi.nii.gz

BOLD (Blood oxygen level dependent image): sub-01_ses-forrestgump_func_sub-01_ses-forrestgump_task-forrestgump_acq-dico_run-01_bold.nii.gz

Part 1: : simple plotting with matplotlib

a) Basic plotting: replicate the figure below, but use the ‘jet’ colormap instead of the ‘gray’ colormap (which I used to create the figure below).

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Part 1a: plotting the middle z-slice for each image type.

b) Use the np.min() and np.max() functions to create minimum and maximum intensity projections respectively (see below) of the SWI and the TOF. Show views from all 3 axes and use jet colormap to display your results. *hint for the SWI, you will probably want to restrict the MIP to ~50-100 slices, and use vmax=300 for the TOF (to better highlight the arteries).

Part 1b: plotting the maximum intensity projection and minimum intensity projection for TOF and SWI

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Part 2): contrast estimation

Using numpy, get 3 different contrast measures for each image (root mean square, Michelson, and entropy, see lecture 3 slide 4, 5). Report the contrast (all 3 values) in the title of the plots in figure 1a. base your contrast estimation on the entire 3D or 4D image (not just the slice shown in the figures).

Part 3 : SNR estimation, quantifying noise

<ol>
<li>a) &nbsp;Using the method outlined in the lecture 3 slide 7, report the SNR for each of the modalities.
Which modality has the highest SNR and which has the lowest?
</li>
<li>b) &nbsp;Plot histograms of the noise in each image. What type of distribution does the noise follow?</li>
</ol>
To display the solution to part 3, create a new figure (as in part 1) and display the noise histogram of each image (instead of the image itself) in each sub plot. Show the SNR as the title above each histogram (along with the image name).

*caution – when selecting your noise patch, be sure the patch isn’t all zeros, otherwise your noise will be estimated as 0 and the SNR will be infinite*

Part 4: Denoising

<ol>
<li>a) &nbsp;Using the Fourier transform method shown at end of assignment 1 video and the 3d gaussian,
apply linear filtering to each image for 𝜎 = 2, 𝜎 = 4, and 𝜎 = 15. Create 3 new versions of the figure in part 1a, one figure for each sigma. Show the middle z-slice of the filtered image in all subplots.
</li>
<li>b) &nbsp;Install the ‘dipy’ package and use nlmeans to denoise the images. Show, for each image, the following plots 1) noisy image 2) denoised image 3) method noise (noisy minus denoised), see below for an example on the T1.</li>
</ol>
Submission: Put all your figures in your pdf, along with the code used to generate them and any comments you have about the work, and upload to moodle. If you work with a partner, be sure to include both names on the first page of the report.

</div>
</div>
</div>
