# Android SIG meeting
20th July 2021

# Topics discussed

- Self Introduction
- Introduction to Android SIG
  - The preliminary charter
    - Q: The precondition to get Google involved?
    - D: Meet the completeness and compatibility requirement, HW board, Android partnership
    - Q: Any board available for Android development?
    - D: With radio, codec, camera/isp, sensor modules, like a phone?
    - D: Most of boards current available can not meet Android requirement; not enough cpu performace; lack of peripherals support(GPU, security, biometrics)
    - D: Need to get boards vender involved.
    - Q: Anyone knows the project maintainer for the whole android project?
    - David: Will introduce Google US window with Mark for Android partnership
  - Current projects status
- Near term Plan
  - Tasks breakdown
    - Q: XTS and other upstream blockers should be added to the list and have higher priority than optimizations
    - D: Some tasks can not make progress until the corresponding HW/SW dependency are ready
  - Projects/Code management
    - Q: How to place the 80+ software gits?
    - D: Need to have a repo environment that all those interesting members and individuals they can work together
    - D: We should be able to reproduce Android for RV environment with official AOSP repe and these gits contain, RV changes, the RISC-V related changes should keep compatibility with other arch.
    - Zheng: Call for suggestions and volunteers

# Actions
Google need HW before joinning, who can give a board.

How many tests are still failling in CTS.

David will introduce Google US window with Mark for Android partnership.
