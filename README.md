# Delete branches after merge

1. Expect the `develop` branch not to be removed after merge to `main`. We achieve this by simply adding `develop` to protected branches
2. Deleting feature branches after their code [was successfully merged](https://github.com/mlebkowski/delete-branches-after-merge/pull/2)
3. The branch was succesfully removed, and can be restored with ease. Either by a click of a button, or by simply pushing from local

   ![CleanShot 2023-01-25 at 11 02 41@2x](https://user-images.githubusercontent.com/848731/214534658-3e98a1c0-8afc-4a75-8682-27e40931000d.png)

4. It can be easily recreated by a push from local

   ![CleanShot 2023-01-25 at 11 07 40@2x](https://user-images.githubusercontent.com/848731/214535800-c20664e6-d6e1-458c-890e-6a39ebaffe76.png)

5. Even [after a successfull PR merge](https://github.com/mlebkowski/delete-branches-after-merge/pull/4), this branch remains, because it has [another PR open](https://github.com/mlebkowski/delete-branches-after-merge/pull/3)
