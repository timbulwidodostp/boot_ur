# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Individual Unit Root Tests without multiple testing control Use boot_ur (bootUR) With (In) R Software
# MBB bootstrap ADF test (with intercept and trend) on each individual series (no multiple testing correction) Use boot_ur (bootUR) With (In) R Software
install.packages("bootUR")
library("bootUR")
boot_ur = read.csv("https://raw.githubusercontent.com/timbulwidodostp/boot_ur/main/boot_ur/boot_ur.csv",sep = ";")
# Estimation
# Individual Unit Root Tests without multiple testing control Use boot_ur (bootUR) With (In) R Software
# MBB bootstrap ADF test (with intercept and trend) on each individual series (no multiple testing correction) Use boot_ur (bootUR) With (In) R Software
boot_ur <- boot_ur(boot_ur[, 2:21], bootstrap = "MBB", B = 399, union = FALSE, deterministics = "trend", detrend = "OLS", do_parallel = FALSE)
boot_ur
# Individual Unit Root Tests without multiple testing control Use boot_ur (bootUR) With (In) R Software
# MBB bootstrap ADF test (with intercept and trend) on each individual series (no multiple testing correction) Use boot_ur (bootUR) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished