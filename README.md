# Solar Flare Prediction with a Machine-Learning Algorithm


We try to estimate M-and X-class solar flares **(A solar flare is a sudden flash
of increased brightness on the Sun, usually observed near its surface and
in close proximity to a sunspot group. Powerful flares are often, but not
always, accompanied by a coronal mass ejection. The classification system
for solar flares uses the letters A, B, C, M or X, according to the peak flux in
watts per square metre (W/m2) of X-rays with wavelengths 100 to
800 picometres (1 to 8 angstroms), as measured at the Earth by
the GOES spacecraft.)** utilizing a machine learning algorithm called **Support
Vector Machine (SVM)**, and information is taken from the **Solar Dynamics
Observatory's Helioseismic and Magnetic Imager**. Most flare estimating
endeavours portrayed in the writing use all things considered view
magnetograms or a moderately modest number of ground-based vector
magnetograms. We gather information regarding flaring and non-flaring
active regions sampled from a database of 2,071 active regions, comprised
of 1.5million active region patches of vector magnetic field data, and
characterize each active region by 25 parameters. We then train and test
the machine-learning algorithm and we estimate its performances using
forecast verification metrics with an emphasis on the True Skill Statistic
(TSS).

# Step 1-Identifying Active region-

To train a flare forecasting algorithm, we need a dataset of flaring and nonflaring Active Regions, respectively called positive and negative examples.
An active region is an area with an especially strong magnetic field. Most
solar storms - solar flares and coronal mass ejections (CME) - blast forth
from active regions.
Definitions of positive and negative classes-An active region that flares
within 24 hours after a sample time belongs to the positive class.
Conversely, an active region that does not flare within 24 hours after a
sample time belongs in the negative class.
