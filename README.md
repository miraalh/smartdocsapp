Desktop:
![screen shot 2018-05-28 at 11 43 14 pm](https://user-images.githubusercontent.com/19476588/40642181-253391c0-62d1-11e8-97ab-429e56921e38.png)
![screen shot 2018-05-28 at 11 43 50 pm](https://user-images.githubusercontent.com/19476588/40642194-2e3a840e-62d1-11e8-9e17-74807ddaad6c.png)
![screen shot 2018-05-28 at 11 44 23 pm](https://user-images.githubusercontent.com/19476588/40642201-31329b7e-62d1-11e8-8ad9-8d54235dd447.png)

Mobile:


![mobile-all](https://user-images.githubusercontent.com/19476588/40642567-52eba49e-62d2-11e8-9108-cd553cd539d5.png)
![mobile-doc](https://user-images.githubusercontent.com/19476588/40642568-53067972-62d2-11e8-8545-6f2c8993f339.png)
![mobile-facilities](https://user-images.githubusercontent.com/19476588/40642569-5320d718-62d2-11e8-9f0e-d5678f2a4bdf.png)
![mobile-createnew](https://user-images.githubusercontent.com/19476588/40642588-5d54368a-62d2-11e8-80f5-699629a0b743.png)

# Generated files
This repository contains generated files and a checksum.

**Do not edit the files in this repository outside of an instance of ServiceNow.**

If you find yourself unable to import your repository due to the presence of files edited outside an instance of ServiceNow, merge commits that mix files from different revisions, or other data that does not match the checksum, you may recover using either of the following techniques:
* Remove the problem commits:
  1. Clone your repository to a personal computer with the git command line tools installed and open a git command prompt in the repository root
  2. Run `git log` and take note of the SHA1s of the problem commits
  3. Build revert commits using `git revert SHA1` repeatedly, working backward in time, for each commit that introduced changes not generated by a ServiceNow instance
  4. Run `git push`

* Overwrite the problem code snapshot with a known good one:
  1. Clone your repository to a personal computer with the git command line tools installed and open a git command prompt in the repository root,
  2. Locate a known good code snapshot and record its SHA1. For this step, `git log` can be useful.
  2. Run `git reset --hard SHA1` to a commit that was generated by a ServiceNow instance
  3. Run `git reset HEAD{1}`
  4. Run `git add -A`
  5. Run `git commit`
  6. Run `git push`
