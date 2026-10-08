# pgdg-rpms-docs

Reference pages for the PostgreSQL RPM repository, served with GitHub Pages
at https://pgdg-packaging.github.io/pgdg-rpms-docs/

- `build-order/`: build and runtime dependencies between the packages in
  [pgrpms](https://git.postgresql.org/gitweb/?p=pgrpms.git), per distro, with
  the build steps for each package. `data.json` is generated from the specs
  with `rpmspec`; it shows pgrpms master at the commit named in the commit
  message.

## Licence

MIT licence; see [LICENSE.txt](LICENSE.txt).
