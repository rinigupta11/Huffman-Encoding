# Vocab Term Definitions 
Rini Gupta

Applied Time Series Analysis (DATA 330)

Exam 1 

2/28/21

## Section 0 
| Term | Definition |
|--|--|
|*runtime*|The period of time when a program is running. It begins when a program is opened (or executed) and ends with the program is quit or closed (Christensson, 2006).
|*kernel*| The foundational layer of an operating system (OS). It functions at a basic level, communicating with hardware and managing resources, such as RAM and the CPU (Christensson, 2017).
|*sum of the squares*| The foundational layer of a statistical technique used in regression analysis to determine the dispersion of data points. In a regression analysis, the goal is to determine how well a data series can be fitted to a function that might help to explain how the data series was generated (Kenton, 2020).  
|*degree of freedom*| The number of independent values or quantities which can be assigned to a statistical distribution (Degree of Freedom, 2019).

## Section 1.1 

| Term |Definition  |
|-----|--------|
|  *random (variable)*| A quantity having a numerical value for each member of a group, especially one whose values occur according to a frequency distribution (Oxford Language, 2021). A function defined on a sample space, $\Omega$  (Woodward, 2017).    
|*real numbers*|The real numbers are all numbers that can be represented as fractions (rational numbers), whether proper or improper—and all numbers in between the rational numbers.  The real numbers contain all integers, all fractions, and all irrational (and transcendental) numbers, such as π, e, and 2½ (Stark, 2019).       
| *observation* |  An instance of a random variable, y=Y(ω) for a given ω∈Ω , and it is also a real number (Woodward, 2017). 
| *stochastic* | A collection of random variables where all random variables are defined on the same sample space (Woodward, 2017).
|*time*|The indefinite continued progress of existence and events in the past, present, and future regarded as a whole (Oxford Languages, 2021).  
| *time series* | A set of regular time-ordered observations of a quantitative characteristic of an individual or collective phenomenon taken at successive, in most cases equidistant, periods/points of time (Giovanni, 2001). A realization of a stochastic process (Woodward, 2017). 
| *continuous* | A set of data is said to be continuous if the values belonging to the set can take on ANY value within a finite or infinite interval; a continuous time series is one that exists at all instants of time during which it occurs (Bressler, 2013).  
|*discrete*| A set of data is said to be discrete if the values belonging to the set are distinct and separate (unconnected values); a discrete time series is one which exists only at discrete instants of time (Bressler, 2013).   
| *realization*| The set of values that result from the occurrence of some observed event x(t);t∈T (Woodward, 2017).    
|*ensemble*| The stochastic process is considered to generate the infinite collection (called the ensemble) of all possible time series that might have been observed. Every member of the ensemble is a possible realization of the stochastic process (Bressler, 2013).   
|*expected value*| A predicted value of a variable, calculated as the sum of all possible values each multiplied by the probability of its occurrence (Oxford Languages, 2021).  
|*ordinate*| In a system of coordinates, the y-coordinate, representing the distance from a point to the horizontal or x-axis measured parallel to the vertical or y-axis (Oxford Languages, 2021).
|*abscissa*|In a system of coordinates, the x-coordinate, the distance from a point to the vertical or y-axis measured parallel to the horizontal or x-axis (Oxford Languages, 2021).    
|*covariance*| The mean value of the product of the deviations of two variates from their respective means (Oxford Languages, 2021).
|*autocovariance*| The sequence of covariances of a stationary process. The covariance within the same time series (Woodward, 2017).  
|*autocorrelation*| Correlation between the elements of a series and others from the same series separated from them by a given interval (Oxford Languages, 2021).|


## Section 1.2  
 
| Term | Definition |
|--|--|
| *stationarity* |"Statistical equilibrium" where the mean is not dependent on time so it is possible to estimate the mean from a single realization (Woodward, 2017). 
|*ergodic*| Stochastic process is one whose time statistics equal its ensemble statistics (Woodward, 2017). 
|*strictly stationary*| For any two times in the time series, the distributions must be the same. Additionally, all bivariate distributions must be the same for all values of h (in X(t+h))  (Woodward, 2017). 
|*covariance stationarity*| When $E[X(t)] = \mu$ and is constant for all values of $t$ , $Var[X(t)]=\sigma^2<\infty$ (i.e. is finite for all $t$), $\gamma(t_1, t_2)$ depends only on the lag $t_2-t_1$ (Woodward, 2017).
|*Cauchy-Schwartz inequality*| The absolute value of $\gamma(h)$ is less than or equal to $\gamma(0)$ for all $h$ (Woodward, 2017). 
|*sample autocovariance function*|The estimate of the autocovariance function from a single realization that best preserves the overall pattern of the autocovariance function (Woodward, 2017). 
|*sample autocorrelation function* |The natural estimator for the autocorrelation function (Woodward, 2017). 
|*time domain*| An analysis of physical signals, mathematical functions, or time series of economic or environmental data, in reference to time. Also, in the time domain, the signal or function's value is understood for all real numbers at various separate instances in the case of discrete-time or the case of continuous-time (Time Domain Analysis vs Frequency Domain Analysis: A Guide and Comparison, 2020).
|*frequency domain*| An analysis of signals or mathematical functions, in reference to frequency, instead of time. As stated earlier, a time-domain graph displays the changes in a signal over a span of time, and frequency domain displays how much of the signal exists within a given frequency band concerning a range of frequencies. Also, a frequency-domain representation can include information on the phase shift that must be applied to each sinusoid to be able to recombine the frequency components to recover the original time signal (Time Domain Analysis vs Frequency Domain Analysis: A Guide and Comparison, 2020).
|*Hertz*|The SI unit of frequency, equal to one cycle per second (Oxford Languages, 2021).
|*aperiodic*| Not periodic; occurring irregularly (Aperiodic Definition and Meaning, 2010). 
|*spectral density*| A frequency domain representation of a time series that is directly related to the autocovariance time domain representation (Estimating the Spectral Density, 2020); the Fourier transformation of the autocorrelation (Woodward, 2017). 
|*periodogram*| Information about the relative strengths of the various frequencies for explaining the variation in the time series. (Estimating the Spectral Density, 2020); the fundamental tool of spectral analysis used to estimate the spectral density of a signal (Woodward, 2017).
|*decibels*|A unit used to measure the intensity of a sound or the power level of an electrical signal by comparing it with a given level on a logarithmic scale (Oxford Languages, 2021).
|*Parzen window*| A technique for nonparametric density estimation, which can also be used for classification. Using a given kernel function, the technique approximates a given training set distribution via a linear combination of kernels centered on the observed points. (Brown, 1999); A probability density function that acts as a method for smoothing the the sample spectrum by implementing a truncation point (Woodward, 2017).
|*AR(1)*|A linear model that predicts the present value of a time series using the immediately prior value in time (Sample ACF and Properties of AR(1) Model, 2020).

  
## References
Aperiodic Definition and Meaning. (2010). Retrieved March 01, 2021, from https://www.collinsdictionary.com/us/dictionary/english/aperiodic

Bressler, S. L. (2013). Time Series and Stochastic Processes. Retrieved March 01, 2021, from http://www.ccs.fau.edu/~bressler/EDU/STSA/Modules/I.pdf

Brown, M. (1999, November 5). Parzen Windows. Retrieved March 01, 2021, from [https://compbio.soe.ucsc.edu/genex/genexTR2html/node11.html](https://compbio.soe.ucsc.edu/genex/genexTR2html/node11.html)

Christensson, P. (2017, January 13). Kernel Definition. Retrieved 2021, Mar 3, from [https://techterms.com](https://techterms.com)

Christensson, P. (2006). Runtime Definition. Retrieved 2021, Mar 3, from [https://techterms.com](https://techterms.com)

Estimating the Spectral Density. (2020, September 26). Retrieved March 01, 2021, from https://online.stat.psu.edu/stat510/lesson/12/12.1

Giovannini, E. (2001, September 25). OECD Glossary of Statistical Terms. Retrieved March 01, 2021, from [https://stats.oecd.org/glossary/detail.asp?ID=2708](https://stats.oecd.org/glossary/detail.asp?ID=2708)

Kenton, W. (2020, June 27). Sum of Squares. Retrieved March 03, 2021, from [https://www.investopedia.com/terms/s/sum-of-squares.asp](https://www.investopedia.com/terms/s/sum-of-squares.asp)

Oxford languages and Google - English. (n.d.). Retrieved March 03, 2021, from https://languages.oup.com/google-dictionary-en/

Sample ACF and Properties of AR(1) Model. (2020, September 26). Retrieved March 01, 2021, from https://online.stat.psu.edu/stat510/lesson/1/1.2

Stark, P. B. (2019, September 2). Glossary of Statistical Terms. Retrieved March 1, 2021, from https://www.stat.berkeley.edu/~stark/SticiGui/Text/gloss.htm

Time Domain Analysis vs Frequency Domain Analysis: A Guide and Comparison (1223922544 910230131 C., Trans.). (2020). Retrieved March 01, 2021, from [https://resources.pcb.cadence.com/blog/2020-time-domain-analysis-vs-frequency-domain-analysis-a-guide-and-comparison](https://resources.pcb.cadence.com/blog/2020-time-domain-analysis-vs-frequency-domain-analysis-a-guide-and-comparison)

Woodward, W. A., Gray, H. L., & Elliott, A. C. (2017). Applied time series analysis with R. Boca Raton, FL: CRC Press, Taylor & Francis Group. 
