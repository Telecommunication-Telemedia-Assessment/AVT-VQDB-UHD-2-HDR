# AVT-VQDB-UHD-2-HDR
An 8K HDR dataset published by the AVT group of TU Ilmenau

This is a repository with data related to the 8K HDR dataset that is published at QoMEX 2024.
However, to download the videos it is recommended to use the provided tool, because the videos are not hosted in this repository.
This work is part of the Interconnected Lab for MEdia Technology Analytics (ILMETA), funded by Deutsche Forschungsgemeinschaft (DFG, No. 438822823) and it is conducted in the framework of PoQuMo8K, a ZIM project (No. KK5112706ER1).

If you use any of the data or code please cite the following paper

```bibtex
@inproceedings{keller2024avt,
    author = {Dominik Keller and Thomas Goebel and Valentin Siebenkees and Julius Prenzel and Alexander Raake},
    title = {AVT-VQDB-UHD-2-HDR: An open 8K HDR source dataset for video quality research},
    booktitle="2024 16th International Conference on Quality of Multimedia Experience (QoMEX)",
    year = {2024}
}
```
## Dataset

![thumbnails](github_images/thumbnails.png)
*Thumbnails of the 31 sources (converted to Rec 709 for viewing purposes)*

## Download
Download the sources: [https://forms.gle/Ptq9NvZe8tKpnJXx6]([https://forms.gle/Ptq9NvZe8tKpnJXx6](https://docs.google.com/forms/d/e/1FAIpQLSeue0AVOvSTZtFcis-SEqY3O4juzW4iUBJ7hFCO2TlVhrOJxQ/viewform?usp=sf_link))

Find the objective metric data in this git.

Use the provided download tool for your system to get all the sources.
Under Linux, `wget` needs to be installed; then you can execute the Shell-script.
```bash
./download.sh
```

Under Windows, execute the batch script:
```bat
.\download.bat
```
## Checksums   

SHA-512 checksums can be found [here](https://avtshare01.rz.tu-ilmenau.de/avt-vqdb-uhd-2-hdr/checksums.sha512).
MD5 checksums can be found [here](https://avtshare01.rz.tu-ilmenau.de/avt-vqdb-uhd-2-hdr/checksums.md5).

![](https://avtshare01.rz.tu-ilmenau.de/asstt/glo.php?key=0ac46938ffb810873bf393adff8b1529&p=uhd2)

## License
This database consists of short term videos that are created from scratch by TU Ilmenau. The tools provided in this repository can be used to download the shared videos that are used in the described video quality tests.
Our own contents follow the [Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) licence.

