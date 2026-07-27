# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit Generalized Pareto Distribution (POT method) Use fpot (evd) With (In) R Software
install.packages("evd")
library("evd")
# Estimation Fit Generalized Pareto Distribution (POT method) Use fpot (evd) With (In) R Software
fpot = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fpot/main/fpot/fpot.csv",sep = ";")
fpot <- fpot$fpot
fpot_ <- as.numeric(fpot)
u <- quantile(fpot, 0.90)
fpot_u <- fpot(fpot_, threshold = u)
fpot_1 <- fpot(fpot_, threshold = 1)
fpot_u
fpot_1
# Fit Generalized Pareto Distribution (POT method) Use fpot (evd) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished