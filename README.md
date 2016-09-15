Biometric Exploratory Analysis Creation House (BEACH) is a shiny app that provides automation platform for users.

Before running BEACH, please make sure your computer is connected to internet and the following packages are installed.

dep.packages <- c("shiny", "DT", "haven", "xtable", "rtf", "plyr", "sas7bdat", "WriteXLS", "SASxport");
install.packages(dep.packages);

Please set up your default internet browser as google chrome
Then, in your R console, please run the following code to run BEACH locally.

library(shiny);
runGitHub("BEACH", "DanniYuGithub");

