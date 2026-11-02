# Kernel build pack (mt6768 lancelot/merlin, 4.19)

Copy into the ROOT of your kernel repo (keep paths):
  ksun.env
  .github/workflows/build.yml
  patches/

Run: GitHub -> Actions -> "Build Kernel (mt6768)" -> Run workflow.
Output: IceStoRM-<device>-<date>.zip (flash via recovery) in the run's Artifacts.
