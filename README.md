![bash_unit CI](https://github.com/pforret/m1_ssd_tbw/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/m1_ssd_tbw/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/m1_ssd_tbw)
![GH stars](https://img.shields.io/github/stars/pforret/m1_ssd_tbw)
![GH tag](https://img.shields.io/github/v/tag/pforret/m1_ssd_tbw)
![GH License](https://img.shields.io/github/license/pforret/m1_ssd_tbw)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

# m1_ssd_tbw

Measure SSD wear (TBW) on MacOS M1 (ARM64) machines

## Background

* [M1 Mac owners are experiencing extremely high SSD writes (Feb 17, 2021)](https://linustechtips.com/topic/1306757-m1-mac-owners-are-experiencing-extremely-high-ssd-writes-over-short-periods-of-time-likely-thanks-to-aggressive-swap/)

        The most severe cases have "consumed" about 10-13% of the maximum warrantable TBW value of the SSDs
  
* [@marcan42 (Feb 16, 2021)](https://twitter.com/marcan42/status/1361722552238841860)

        Update on M1 SSD wear issue: 
        Available data suggests that write endurance ratings are not proportional to drive size.

        256GB model: ~2000TB [1700-2300]
        2TB model: ~5000TB [4300-6000]

* [SSD Lifespan: How Long do SSDs Really Last? (July 30, 2020)](https://www.ontrack.com/en-us/blog/how-long-do-ssds-really-last)
        
        A typical TBW figure for a 250 GB SSD lies between 60 and 150 terabytes written

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/m1_ssd_tbw

or with `git`

	$ git clone https://github.com/pforret/m1_ssd_tbw.git
	$ cd m1_ssd_tbw

## 🔥 Usage

	> m1_ssd_tbw.sh [action]

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2021 Peter Forret
