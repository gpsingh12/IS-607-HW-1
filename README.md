# IS-607-HW-1

###Flags

The dataset Flags is chosen from UCI Machine Learning Repository.

Reading the data from repository and creating a data frame


y<- "https://archive.ics.uci.edu/ml/machine-learning-databases/flags/flag.data"

x <- read.table(y, header = FALSE, sep = ",")


Assigning names to the dataset attributes


names(x) <- c("country", "landmass", "zone", "area", "population", "language",  "religion", "bars", "stripes", "colors", "red", "green", "blue","gold", "white", "black", "orange","mainhue", "circles", "crosses", "saltires", "quarters", "sunstars","crescents", "triangle", "icon", "animate", "text", "topleft", "botright")

