MOST Release Notes
==================

What's New in Version 1.0.1
---------------------------

Below is a summary of the changes since version 1.0 of MOST. See the
[`CHANGES.md`][1] file for all the gory details. For release notes for
previous versions, see Appendix B of the [MOST User's Manual][2].

* Bugs fixed:
  - Fix bugs in `plot_uc_data()` resulting in incorrect legends.
  - Fix dimension of `RampWear` cost indexing if `mdi.OpenEnded` is true.
  - Add missing constant term to objective function value reported by
    `most_summary`.

* Other Changes:
  - Updated to use OOP notation for `opt_model` object, and avoid calls
    to deprecated methods, using `init_indexed_name()` and
    `add_lin_constraint()` instead.
  - Updated to use MATPOWER's new quadratic costs in `opt_model` in
    place of the legacy cost model.


[1]: ../../CHANGES.md
[2]: ../MOST-manual.pdf
