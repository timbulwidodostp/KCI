# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Kernel conditional independence test Use KCI (CondIndTests) With (In) R Software
install.packages("CondIndTests")
library("CondIndTests")
KCI = read.csv("https://raw.githubusercontent.com/timbulwidodostp/KCI/main/KCI/KCI.csv",sep = ";")
# Estimation Kernel conditional independence test Use KCI (CondIndTests) With (In) R Software
KCI(KCI$Y, KCI$E, KCI$X)
KCI(KCI$Y, KCI$X, KCI$E)
# Kernel conditional independence test Use KCI (CondIndTests) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished