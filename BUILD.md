# Build and Review Guide

This repository is the submission-facing portfolio for the ED452B Minecraft Innovative Unit Plan.

## What to review first

1. `README.md` - portfolio overview and part map.
2. `parts/part_1_unit_plan_design/report.tex` - Part 1 design report source.
3. `parts/part_2_revised_unit_plan/report.tex` - revised/final report source.
4. `parts/part_3_reflection_presentation/presentation.tex` - Part 3 reflection presentation source.
5. `course_alignment/rubric_alignment.md` - direct rubric map.
6. `appendix/` - assessment tools, transcript analysis, and de-identified evidence records.

## Build LaTeX reports locally

From the repository root:

```bash
latexmk -pdf parts/part_1_unit_plan_design/report.tex
latexmk -pdf parts/part_2_revised_unit_plan/report.tex
latexmk -pdf parts/part_3_reflection_presentation/presentation.tex
```

If `latexmk` is not installed, use `pdflatex` twice for each file:

```bash
pdflatex -output-directory parts/part_2_revised_unit_plan parts/part_2_revised_unit_plan/report.tex
pdflatex -output-directory parts/part_2_revised_unit_plan parts/part_2_revised_unit_plan/report.tex
```

Repeat with the Part 1 and Part 3 source paths.

## Final submission checklist

- Confirm the repository has been renamed to `ED452B-Innovative-Unit-Plan-Portfolio`.
- Compile Part 2 into PDF for the primary written submission.
- Compile Part 3 into PDF if slides are submitted as a static deck.
- Keep raw transcripts, student names, IEP records, and identifiable student work out of this public repository.
- Submit the final PDF, repository link, and any course-required appendix artifacts through the LMS.

## Privacy rule

Public documentation should use only de-identified and synthesized placement evidence. Raw TeachingPlacement transcript material should stay private unless explicitly approved for course submission.
