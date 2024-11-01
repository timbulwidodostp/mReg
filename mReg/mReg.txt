# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Multiple regression Use mReg (berryFunctions) With (In) R Software
install.packages("berryFunctions")
library("berryFunctions")
mReg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mReg/main/mReg/mReg.csv",sep = ";")
# Estimation Multiple regression Use mReg (berryFunctions) With (In) R Software
mReg <- mReg(Dependen~Independen_1+Independen_2, data=mReg)
print(mReg)
# Multiple regression Use mReg (berryFunctions) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished