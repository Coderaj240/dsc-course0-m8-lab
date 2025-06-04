# Aviation Accident Analysis

# Part-1
- Aviation_Accidents_Cleaning file was opened in juypter notebook. The files were forked in git hub and required csv data downloaded  from Kaagle web. The csv file is put in local repository using push. In aviation_accidents_cleaning file, pandas was used to load, inspect, and clean the dataset appropriately. The relavant columns were transformed  to create measures that address the problem at hand. EDA:  visualization and statistical measures to systematically understand the structure of the data conduted.
- the cleaned file is saved into data folder.


# Part-2
- the cleaned save data was explored and safety metrics across models was explored.
- The analyzing makes were created and Explored the human injury risk profile for small and larger Makes:
- Distribution of injury rates: small makes & large makes created.
- evaluated the rate of aircraft destruction for both small and large aircraft by Make.

# the rate of aircraft destruction for both small and large aircraft by Make were evaluated.
# a short discussion on your findings for my summary statistics and plot was provided. The following discussion was made.


# Discussion on  what I have found above regarding passenger fraction seriously/ both small and large airplane models.
# Large aircraft: Top makes have consistently low rates of serious/fatal injuries; most accidents result in little or no serious harm to passengers.
# Small aircraft: The safest makes still have more variability and occasional high-injury outliers, meaning outcomes are less predictable.
 Overall, large aircraft are safer for passengers in terms of serious/fatal injuries, while small aircraft, even among the best makes, show greater risk variation.

### Exploring Other Variables
 Investigate how other variables effect aircraft damage and injury. You must choose **two** factors out of the following but are free to analyze more: I took 1. Weather Condition & Number of Engines vs. Injury/Destruction 

#### 1. Weather Condition

**Analysis:**  
We grouped accidents by the reported weather conditions and calculated both the mean serious/fatal injury fraction and the mean destruction rate. Barplots were used to compare the average severity of accidents across weather categories.

**Visualization:**  
- Barplot of mean serious/fatal injury fraction by weather condition.
- Barplot of mean destruction rate by weather condition.

**Findings & Interpretation:**  

- Accidents occurring in **Instrument weather conditions**  have noticeably higher mean serious/fatal injury fractions and destruction rates compared to those in **Visual conditions** (clear weather).

- This suggests that adverse weather increases the severity of accidents, possibly due to reduced pilot visibility, more difficult flying conditions, and a higher likelihood of loss-of-control accidents.


#### 2. Engine Type
 **Analysis:**  
# Accidents were grouped based on the aircraft's engine type (e.g., Piston, Turbojet, Turboprop, Turbofan) . For each engine type, we computed the mean serious/fatal injury fraction and mean destruction rate. These were visualized using barplots.

**Visualization:**  
 - Barplot of mean serious/fatal injury fraction by engine type.
#-- Barplot of mean destruction rate by engine type.

**Findings & Interpretation:**  
 - **Jet and turbofan engines** (common in large, commercial aircraft) are associated with lower mean serious/fatal injury fractions and lower destruction rates than **piston engines** (common in smaller, general aviation planes).

- This may be due to stricter safety regulations, higher build quality, better safety features, and more experienced crews in commercial aviation.
- Piston-engine aircraft often operate in less controlled environments and may be more susceptible to severe accidents.



#### Summary Table Example

| Factor            | Safest Category    | Highest Risk Category   |
|-------------------|-------------------|------------------------|
| Weather Condition | Visual            | Instrument             |
| Engine Type       | Turbofan/Jet      | Piston                 |


#### Recommendations
 # - **Extra caution and risk mitigation** is needed for operations in poor weather.
# - **Piston-engine aircraft** operations may benefit from enhanced safety focus, training, or inspection, as they are involved in more severe outcomes on average.
# -This analysis can inform safety training, risk assessment, and insurance policy decisions.