# comp3270-assignment-1-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [COMP3270 Assignment 1-Algorithms Solved](https://www.ankitcodinghub.com/product/comp-3270-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131823&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3270 Assignment 1-Algorithms Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Overview

To empirically evaluate 4 sorting algorithms and verify their theoretical upper bound. The sorting algorithms we will evaluate are: merge sort, quick sort, insertion sort, and selection sort. A starter code with helper functions and implementations of 2 algorithms (selection sort and merge sort) has been provided. Your task is to implement the remaining two sorting algorithms (quick sort and insertion sort) and perform the following empirical analyses. You will run a specific algorithm on three different types of arrays – sorted, random, or constant array of a given size n. The provided starter code will generate the input arrays for your analysis. The starter code will take as input three command line arguments in the following order:

1. Type of input array. You have three choices: ‘r’, ‘c’, and ‘s’ that correspond to random, constant and sorted arrays, respectively. If invalid values are given, it will default to a random input array.

2. Size of the array to generate and analyze. It must be a positive number greater than zero. It will default to 10 if an invalid value is provided.

3. Sorting algorithm to use. You have four choices: ‘m’, ‘i’, ‘s’, and ‘q’ that correspond to merge sort, insertion sort, selection sort, and quick sort, respectively. If an invalid value is given, it will default to quick sort.

If an incorrect number of arguments are given or if an integer is not provided for the second command line argument, it will default to running quick sort on a random input array of size 10. For stable computation of timing, the starter code will run each algorithm three times and provides the median of the three runs. For accurate timing, ensure that there are no other processes running on the machine while you conduct your analysis. The output timing will be in nanoseconds.

2. Deliverables:

There are two deliverables for this programming project: (i) the completed code with the two sorting algorithms completed in the functions marked with “TODO”, and (ii) a report with your analysis clearly marked with two sections – “Results” and “Analysis.” More details about what is expected to be presented in each section are provided below.

2.1 Results

Run each of the four sorting algorithms on constant, sorted, and random arrays that are powers of 10. For each of the twelve cases, you should record the following:

• Nmin: the smallest power of 10 array size that takes 20 milliseconds or more per run to sort.

• Nmax: the largest power of 10 array size that takes 10 minutes or less per run to sort (30 mins for all 3 runs), or the largest input size you can successfully sort if no input took more than 30 minutes total.

• Tmin: the time to sort an array of size Nmin.

• Tmax: the time to sort an array of size Nmax.

You should report your results in a table. Your table should have 12 rows and 5 columns. Each row must have a label with 2 letters, where the first corresponds to the algorithm (Merge, Quick, Insertion, or Selection) and the second corresponds to the array type (Sorted, Random, or Constant). For example, SS corresponds to Selection sort run on a Sorted array. An example table is shown below.

2.2 Analysis

In this section, you will estimate the complexity of the four algorithms by comparing the ratio between Tmin and Tmax to ratios representing the complexity of the algorithm. Specically, you should compute f(Nmax) = f(Nmin) for f1(n) = n, f2(n) = n ln(n), and f3(n) = n2. You should round to the nearest integer when computing these ratios. Finally, you should label each experiment according to the ratio Tmax=Tmin most resembles.

For example, if you get Nmin= 10 and Nmax = 100, your ratios would be:

• f1(Nmax)/f1(Nmin) = 100/10

• f2(Nmax)/f2(Nmin) = (100*ln(100))/

(10*ln(10))

• f3(Nmax)/f3(Nmin) = 1002/102

You should then label the algorithm based on which of these three ratios Tmax = Tmin is closest to. As part of your report, you should create a table that includes the computed ratios as well as the behavior of the algorithm (Linear, n lg n, or Quadratic), across all 12 experiments. An example is given below:

Your report should contain a summary of (1) how your results compare to the theoretical analysis for all four algorithms, and (2) why your results make sense or are surprising. You should spend more time explaining your results when they are unusual or unexpected.
