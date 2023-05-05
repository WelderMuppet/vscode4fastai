## check environment in each notebook with this code:

import os
DEVMODE = os.getenv("KAGGLE_MODE") == "DEV"
print(f"DEV MODE: {DEVMODE}")
EPOCHS = 2 if DEVMODE else 30