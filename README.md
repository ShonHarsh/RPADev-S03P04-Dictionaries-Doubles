![](https://shonharsh.github.io/curriculum-vitae/images/uipath-logo.png)

# S03P04 Dictionaries & Doubles

This project is my solution in **C#** to the **Dictionaries & Doubles** practice found in section 03 practice 04 of the UiPath - RPA Developer Foundation course.

### Getting Started

After making a pull request or downloading the project, open the Main.xaml in UiPath Studio.  The robot can be run with the play button in the ribbon and the result can be seen in output pane.

#### PRACTICE REQUIREMENTS

###### **Calculate the combined weight of the packages sent to one city**

Consider the database of a shipping company containing people and the packages they are sending to certain cities across the world, along with their weight. The database is a Dictionary with the key of String type (the names of the persons) and the values of Dictionary (String/Cities, Double/Weight) type.

Please calculate the overall weight for one city destination. Once this is done, the user should be presented with an input dialog containing the distinct list of cities present in the input data dictionary. If the user chooses no value from the input dialog, print "Nothing chosen by the user"; otherwise you can print "The combined weight of the packages sent to <ChosenCity> is x.xx" (use double digits).

**Note**: For input data, download the workflow below, which already has the Dictionary defined.

New Dictionary(Of String, Dictionary(Of String, Double)) From {

{"John C", New Dictionary(Of String, Double) From {{"Madrid",2.1},{"Paris",1.1}}  },

{"Sarah C", New Dictionary(Of String, Double) From {{"New York",2.1},{"Paris",3.3},{"Berlin", 0.8}}  },

{"Kyle R", New Dictionary(Of String, Double) From {{"San Francisco",2.8},{"New York",1.1}}  },

{"Johnny B", New Dictionary(Of String, Double) From {{"New York",2.1},{"Paris",3.3}, {"Cairo",1.3}, {"Chicago",1.9}}  }}

### Details

**Course:** UiPath - RPA Developer Foundation

**Section:** 03 Data Manipulation

**Practice:** 04 Dictionaries & Doubles

**GitHub:** https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles

### Sample Output

```
07/22/2021 10:20:17 => [Debug] Execution started for project: RPADev-S03P04-Dictionaries-Doubles
07/22/2021 10:20:18 => [Info] RPADev-S03P04-Dictionaries-Doubles execution started
07/22/2021 10:20:27 => [Debug] The combined weight of the packages sent to Paris is 7.7.
07/22/2021 10:20:27 => [Info] RPADev-S03P04-Dictionaries-Doubles execution ended in: 00:00:08
```

### Notes

This image shows the dictionary data types.  The pseudocode is:

new Dictionary <String, new Dictionary <String, Double>>

![](https://shonharsh.github.io/curriculum-vitae/images/RPADev-S03P04-Dictionaries-Doubles-VariableDataTypes.png)

### RPA Developer Foundation Sections

1. Get Started With RPA Development

2. Variables, Data Types And Control Flow In Studio

   P01 [RPADev-S02P01-ForEachIfStatement](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement)

   P02 [RPADev-S02P02-GenericValue](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue)

   P03 [RPADev-S02P03-Switch](https://github.com/ShonHarsh/RPADev-S02P03-Switch)

3. Data Manipulation In Studio

   P01 [RPADev-S03P01-Lists](https://github.com/ShonHarsh/RPADev-S03P01-Lists)

   P02 [RPADev-S03P03-Dictionaries-Integers](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers)

   P03 [RPADev-S03P04-Dictionaries-Doubles](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles)

   P04 [RPADev-S03P05-InputValidation](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation)

   P05 [RPADev-S03P06-ReplacingPlaceholders](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders)

   P06 [RPADev-S03P07-ExtractEmailAddress](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress)

   P07 [RPADev-S03P08-ExtractEmailAddressRegEx](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx)

4. Excel And Data Tables With Studio

   P01 [RPADev-S04P01-CalculatingSums](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums)

   P02 [RPADev-S04P02-CalculatingLossInvoices](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices)

   P03 [RPADev-S04P03-CalculatingPercentagesOfExpenses](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses)

5. UI Automation With Studio

   P01 [RPADev-S05P01-PasswordGenerator](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator)

   P02 [RPADev-S05P02-TheRPAChallenge](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge)

   P03 [RPADev-S05P03-InputActions](https://github.com/ShonHarsh/RPADev-S05P03-InputActions)

   P04 [RPADev-S05P04-OutputActions](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions)

   P05 [RPADev-S05P05-DataScraping](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping)

6. Selectors In Studio

   P01 [RPADev-S06P01-GetAndSortData](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData)

   P02 [RPADev-S06P02-SetData](https://github.com/ShonHarsh/RPADev-S06P02-SetData)

   P03 [RPADev-S06P03-Highlight-TypeItems](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems)

7. Project Organization In Studio

   P02 [RPADev-S07P02-StateMachines](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines)

   P03 [RPADev-S07P03-FixMyWorkflow](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow)

   P04 [RPADev-S07P04-Libraries](https://github.com/ShonHarsh/RPADev-S07P04-Libraries)

8. Error And Exception Handling In Studio

9. Debugging In Studio

10. PDF Automation In Studio

11. Email Automation With Studio

12. Orchestrator For RPA Developers

13. Robotic Enterprise Framework Overview

### Requirements

[UiPath Studio](https://www.uipath.com/product/studio) is required to run the robot.

### Git Notes

Clone the project to develop or change it.

`git clone https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles`

### Links

[UiPath: Automation Platform](https://www.uipath.com/)

[UiPath Studio](https://www.uipath.com/product/studio)

[My Website](https://shonharsh.github.io/curriculum-vitae/index.html) - Errors, spelling fixes and comments are very welcome!













