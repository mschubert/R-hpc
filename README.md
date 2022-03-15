# High Performance Computing with the R programming language

This material was developed for a pilot 2-day workshop at the University of Warwick in March 2022, associated with the [Sulis tier 2 HPC service](https://www.sulis.ac.uk) and funded by [EPSRC grant EP/W032201/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/W032201/1).

This version is the material used in the pilot and contains instructions/examples tailored to the Sulis HPC service. It is forked from the upstream repository of [Dr Michael Schubert](https://github.com/mschubert) to retain the Sulis specific elements. 


## Day 1

#### Morning: Intoduction to HPC and the Sulis tier 2 service

* Capabilities of the computing cluster
* How to connect
* Starting a basic job

#### Afternoon: Quick Start

* Copying and editing files via the command-line
* Interactive jobs, batch jobs
* `parallel` package, cluster objects, and `future`

#### Afternoon: Neovim as IDE

* The `Nvim-R` plugin to interactively develop in a remote session
* Persistent server sessions using `tmux`

## Day 2

#### Morning: Breakpoint example

* An MCMC breakpoint detection method as example
* Tasks vs. threads for bigger jobs
* R packages for HPC use: `slurmR` and `clustermq`

#### Afternoon: Workflows

* GNU parallel and GNU make
* Snakemake
* The `targets` R package

#### Afternoon: 

* Possibility for attendees to work on their own projects with help from the instructors
