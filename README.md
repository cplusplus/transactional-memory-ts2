This came from <https://github.com/fraggamuffin/tm_ts2021> which was the repository for
the C++ Technical Specification "Trannsactional Memory TS 2021" for N4906, the TM-TS2 from 2022-02-14:
https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2022/n4906.pdf
It was moved here on Oct 10, 2022 where it will be edited for the DTS ballot comments from P2617
https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2022/p2617r0.html

The draft Technical Specification is found in the `src` directory and is
written in LaTeX. There is a Makefile that can be used to compile the
sources, or you can use the `latexmk` program e.g. `latexmk -pdf ts`
will generate a PDF.

# TM TS2021 Editor's Report

## pre-Kona Nov 2022 Plenary meeting N4923

1.  N4923 revises N4906 and is the DTS of Transactional Memory TS Version 2. It contains changes to the N4906 as directed by the committee at the July-25 2022 virtual plenary meeting, and editorial changes.
2. N4923 revises N4906 with P2617R0 Responses to NB comments on TM-TS2 DTS 12907. It omits the symbolic references in P2517R0 in cross-references as is conventional in these documents and just use the numeric references. 

3. Other than the front matter changes, it also contains the following editorial changes:

      in Sec. 4.2: Michael Scott->Michael L. Scotts

      In 6.9.1 (Line 5.3), “start and the end of an atomic block” -> “start or the end of an atomic block”

      In 6.9.2.2 (Line 21), “An atomic block” ->  “The execution of an atomic block”


## pre-Feb 2022 virtual Plenary meeting N4906

N4906 is the proposed working draft of Transactional Memory TS Version 2. It contains changes to the TM TS2021 as directed by the committee at the June 2021 virtual plenary meeting, and editorial changes.

N4895 contains P2066R10 from Oct 2021 virtual plenary.

## Technical Changes

None

## Notes

None

## Acknowledgements


Hans Boehm
Victor Luchangco
Jens Maurer
Michael L. Scott
Michael Spear
Michael Wong
