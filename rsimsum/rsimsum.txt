# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Analyses of simulation studies including Monte Carlo error Use simsum (rsimsum) With (In) R Software
install.packages("rsimsum")
library("rsimsum")
rsimsum = read.csv("https://raw.githubusercontent.com/timbulwidodostp/rsimsum/main/rsimsum/rsimsum.csv",sep = ";")
# Estimation Analyses of simulation studies including Monte Carlo error Use simsum (rsimsum) With (In) R Software
simsum <- simsum(data = rsimsum, estvarname = "b", true = 0.5, se = "se", methodvar = "method", ref = "CC")
summary(simsum)
# Analyses of simulation studies including Monte Carlo error Use simsum (rsimsum) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished