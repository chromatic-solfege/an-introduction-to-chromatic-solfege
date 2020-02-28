The Source Code of The Paper "An Introduction to Chromatic Solfege"
===================================================================

**Feb 12, 2020 -  This readme is obsolete.**

	+ lytex
		The files in this directory are script files that generate the book
		data for "Chromatic-Solfege" and "Chromatic-Solfege for Guitarists".
		The files are not a part of the system but actual scripts that use the
		system. Please take these as examples to grasp the usage of the system.
		
		- out
			The directory where all output files go. 

		- ch-???-\*
			We call these files as ``ch-scripts''. A ch-scripts contains document
			data and creates tex, lilypond, festival and other scripts.

		- ch-000-chromatic-solfege
			A ch-script to output the data for the book of "Chromatic-Solfege"

		- ch-001-chromatic-solfege-for-guitarists-01
		- ch-002-chromatic-solfege-for-guitarists-02
			A ch-script to output the data for the book of "Chromatic-Solfege for
			Guitarists". The script file was very large that it took hours to compile;
			it divided into two files. the file-01 consists the description and file-02
			consists fretboard-charts.

		- query-fretdiagram-systems-\*
			Temporary files that the node module "chromatic" creates. These file
			can safely be deleted.


	+ tex
		The files in this directory are tex files of "Chromatic-Solfege" and
		"Chromatic-Solfege for Guitarists".  The files are not a part of the
		system. Please take these as practical applications of the system.

		- chromatic-solfege.tex
			The main file for the book "Chromatic-Solfege".

		- chromatic-solfege-for-guitarists.tex
			The main file for the book "Chromatic-Solfege for Guitarists".
		
		- ly-generated
			A symbolic link to "chromatic/lytex/out/" where the all automatically
			generated files go.

		- ly-manual
			All Lilypond scripts for both "chromatic-solfege.tex" and
			"chromatic-solfege-for-guitarists.tex"
