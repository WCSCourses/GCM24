**Genomics and Clinical Microbiology 2024 Software Installation**

# Table of Contents {#table-of-contents .TOC-Heading}

[Introduction to Software Installation
[1](#introduction-to-software-installation)](#introduction-to-software-installation)

[Software list and their version used in course
[1](#software-list-according-to-course-modules)](#software-list-according-to-course-modules)

[Installation of Inkscape [1](#_Toc157521076)](#_Toc157521076)

[Installation of MEGA [2](#installation-of-mega)](#installation-of-mega)

[Installation of SplitsTree
[2](#installation-of-splitstree)](#installation-of-splitstree)

[Installation of BLAST+, SPAdes, QUAST and FASTQC (with CONDA)
[3](#installation-of-blast-spades-quast-and-fastqc-with-conda)](#installation-of-blast-spades-quast-and-fastqc-with-conda)

[Additional Resources and Troubleshooting
[4](#additional-resources-and-troubleshooting)](#additional-resources-and-troubleshooting)

## Introduction to Software Installation

This guide provides extensive instructions for software installation on
Ubuntu/Windows/MacOS systems, applicable to both virtual machine (VM)
and host machine setups, as taught and utilized in the Genomics and
Clinical Microbiology 2024 course. For VM installation specifics, please
consult the supplementary VM installation guide attached separately.
Additionally, valuable troubleshooting links are provided below for
additional assistance.

**Note:** The Virtual Machine file (.vdi) contains all the software
installed for the course.

## Software list according to course modules

+--------+------+----------------+-----+-----------------------------+
| **Mo   | **So | **Summary**    | **  | **Website**                 |
| dule** | ftwa |                | Ver |                             |
|        | re** |                | sio |                             |
|        |      |                | n** |                             |
+========+======+================+=====+=============================+
|        | Inks | Inkscape is a  | 0.9 | <https://inkscape.org/>     |
|        | cape | Free and open  | 2.4 |                             |
|        |      | source [vector |     |                             |
|        |      | graphics       |     |                             |
|        |      | editor](h      |     |                             |
|        |      | ttp://en.wikip |     |                             |
|        |      | edia.org/wiki/ |     |                             |
|        |      | Comparison_of_ |     |                             |
|        |      | vector_graphic |     |                             |
|        |      | s_editors) for |     |                             |
|        |      | GNU/Linux,     |     |                             |
|        |      | Windows and    |     |                             |
|        |      | macOS.         |     |                             |
+--------+------+----------------+-----+-----------------------------+
| Constr | MEGA | Sophisticated  | 11. | <htt                        |
| ucting |      | and            | 0.3 | ps://www.megasoftware.net/> |
| phylog |      | user-friendly  |     |                             |
| enetic |      | software suite |     |                             |
| trees  |      | for analyzing  |     |                             |
|        |      | DNA and        |     |                             |
|        |      | protein        |     |                             |
|        |      | sequence data  |     |                             |
|        |      | from species   |     |                             |
|        |      | and            |     |                             |
|        |      | populations.   |     |                             |
+--------+------+----------------+-----+-----------------------------+
| Constr | Sp   | SplitsTree is  | 4.1 | [**SplitsTree \| University |
| ucting | lits | a widely used  | 8.3 | of                          |
| phylog | Tree | application    |     | Tübingen**](https://un      |
| enetic |      | for computing  |     | i-tuebingen.de/en/fakultaet |
| trees  |      | unrooted       |     | en/mathematisch-naturwissen |
|        |      | phylogenetic   |     | schaftliche-fakultaet/fachb |
|        |      | networks from  |     | ereiche/informatik/lehrstue |
|        |      | molecular      |     | hle/algorithms-in-bioinform |
|        |      | sequence data. |     | atics/software/splitstree/) |
+--------+------+----------------+-----+-----------------------------+
| Introd | BL   | The BLAST+     | 2.1 | <https://blast.n            |
| uction | AST+ | applications   | 5.0 | cbi.nlm.nih.gov/doc/blast-h |
| to the |      | can write the  |     | elp/downloadblastdata.html> |
| Linux  |      | query,         |     |                             |
| c      |      | database, and  |     |                             |
| ommand |      | command-line   |     |                             |
| line   |      | options for a  |     |                             |
| and    |      | BLAST search   |     |                             |
|        |      | into a         |     |                             |
| BLAST  |      | \"strategy\"   |     |                             |
|        |      | file.          |     |                             |
+--------+------+----------------+-----+-----------------------------+
| Genome | SP   | SPAdes Genome  | 3.1 | <https                      |
| as     | Ades | Assembler is   | 5.4 | ://github.com/ablab/spades> |
| sembly |      | an open source |     |                             |
|        |      | tool for de    |     |                             |
|        |      | novo           |     |                             |
|        |      | sequencing.    |     |                             |
+--------+------+----------------+-----+-----------------------------+
| Genome | Q    | QUAST          | 5.  | <http                       |
| as     | UAST | can evaluate   | 2.0 | s://github.com/ablab/quast> |
| sembly |      | assemblies     |     |                             |
|        |      | both with a    |     |                             |
|        |      | reference      |     |                             |
|        |      | genome, as     |     |                             |
|        |      | well as        |     |                             |
|        |      | without a      |     |                             |
|        |      | reference      |     |                             |
+--------+------+----------------+-----+-----------------------------+
| Genome | Fa   | FastQC is used | 0.1 | <https://g                  |
| as     | stQC | to quality     | 2.1 | ithub.com/s-andrews/FastQC> |
| sembly |      | control checks |     |                             |
|        |      | on raw         |     |                             |
|        |      | sequence data  |     |                             |
|        |      | coming from    |     |                             |
|        |      | high           |     |                             |
|        |      | throughput     |     |                             |
|        |      | sequencing     |     |                             |
|        |      | pipelines.     |     |                             |
+--------+------+----------------+-----+-----------------------------+

**Note:** The versions might differ as new releases are enrolled by the
software company.

## Installation of Inkscape

**Download Inkscape:**

Visit the Inkscape website
(<https://inkscape.org/release/inkscape-1.3.2/>) and download the
Windows/MacOS/Ubuntu version of Inkscape.

In Windows and MacOS save the downloaded file and use on-screen
instructions to install Inkscape.

**Installing Inkscape on Ubuntu:**

1.  Open the Terminal on your Ubuntu system.

2.  Add Inkscape Repository: Run the following commands to add the
    Inkscape repository and update the package lists:

![A black screen with white text Description automatically
generated](media/image1.png){width="3.0864752843394574in"
height="0.7073173665791777in"}

3.  Use the package manager to install Inkscape:

![A black and white rectangle with white text Description automatically
generated](media/image2.png){width="3.0912609361329833in"
height="0.573170384951881in"}

4.  Once the installation is complete, you can launch Inkscape from the
    application menu or by running Inkscape in the Terminal.

## Installation of MEGA

**Download MEGA:**

Visit the official MEGA website (<https://mega.io/download>) and
download the Windows/MacOS version of MEGA Sync Client.

In Windows and MacOS save the downloaded file and use on-screen
instructions to install MEGA.

**Installing MEGA on Ubuntu:**

1.  Open the Terminal on your Ubuntu system.

2.  Add MEGA Repository: Run the following commands to add the MEGA
    repository and update the package lists:

![A black screen with white text Description automatically
generated](media/image3.png){width="3.0861111111111112in"
height="0.7715277777777778in"}

3.  Use the package manager to install MEGA:

![A black and white text Description automatically
generated](media/image4.png){width="3.0861111111111112in"
height="0.618497375328084in"}

4.  Once the installation is complete, you can launch MEGA from the
    application menu or by running 'megasync' in the Terminal.

## Installation of SplitsTree

**Download SplitsTree:**

Visit the SplitsTree website (<https://www.splitstree.org/>) and
download the Windows/MacOS/Ubuntu version of SplitsTree.

In Windows and MacOS save the downloaded file and use on-screen
instructions to install SplitsTree.

**Installing SplitsTree on Ubuntu:**

1.  Open the Terminal on your Ubuntu system.

2.  Download SplitsTree:

![A black and white screen with white text Description automatically
generated](media/image5.png){width="3.2194444444444446in"
height="0.8115124671916011in"}

3.  Once the installation is complete, you can run SplitsTree by
    entering the following command in the Terminal:

![A black and grey rectangular object Description automatically
generated](media/image6.png){width="3.2195122484689414in"
height="0.6452329396325459in"}

## Installation of BLAST+, SPAdes, QUAST and FASTQC (with CONDA)

**Conda Overview:**

Conda is an open-source package management and environment management
system that runs on Windows, macOS, and Linux. It simplifies the
installation and management of software packages, ensuring dependencies
are correctly handled.

**Installation Script:**

Ensure you have Conda installed on your system before running the
script.

1.  Create a Conda Environment (Optional): If you prefer to create a
    separate environment for these tools, you can do so by running:

![A black and white text Description automatically
generated](media/image7.png){width="3.3055555555555554in"
height="0.8727799650043745in"}

2.  Add Conda Channels: Add necessary channels for accessing
    bioinformatics packages:

![A black screen with white text Description automatically
generated](media/image8.png){width="3.3055555555555554in"
height="0.8943099300087489in"}

3.  Installations of software and verify:

![A screen shot of a computer Description automatically
generated](media/image9.png){width="3.3055555555555554in"
height="1.74375in"}

**Note:** In order to install individual software, use the command line
command "conda install softwareName". For example: conda install spades.

4.  If you created a separate environment, deactivate it:

![A black and grey rectangular object Description automatically
generated](media/image10.png){width="3.3055555555555554in"
height="0.6972222222222222in"}

**Note:**

-   Conda environments provide isolation for different sets of tools,
    enhancing reproducibility.

-   You can customize the script based on your preferences, such as
    creating a dedicated environment or modifying the channels. Activate
    the Conda base environment (conda activate base) if you choose not
    to create a separate environment.

-   By using Conda, this script streamlines the installation process,
    ensuring that the specified bioinformatics tools and their
    dependencies are correctly configured on your system.

-   Save this script to a file (e.g., install_bioinformatics.sh), make
    it executable (chmod +x install_bioinformatics.sh), and run it in
    your terminal (./install_bioinformatics.sh). Adjust the script as
    needed for your specific requirements.

## Additional Resources and Troubleshooting

-   Ubuntu Documentation: <https://help.ubuntu.com/>

-   Ubuntu Community Support:
    <https://ubuntu.com/support/community-support>

-   Conda Installation:
    <https://conda.io/projects/conda/en/latest/user-guide/install/index.html>

-   Conda Documentation:
    <https://conda.io/projects/conda/en/latest/user-guide/getting-started.html#managing-python>

-   Stack overflow: <https://stackoverflow.com/> (Public Q&A platform
    for debugging)

-   Bioinformatics (BioStars) Forum: <https://www.biostars.org/t/Forum/>
    (General Bioinformatics queries)
