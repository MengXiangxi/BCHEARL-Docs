# BCH EARL

> A tool on the Windows system to obtain recovery coefficients from phantoms for PET/CT image harmonization applications.

Developed by Xiangxi Meng, PhD, **B**eijing **C**ancer **H**ospital

## About the project

Harmonization of PET quantification performance is not only important in multicenter clinical trials, but also affects the accuracy in clinical diagnosis. Currently, many influential protocols for PET harmonization involve imaging the NEMA/IEC IQ phantom and obtaining the recovery coefficient (RC) curves, including the [EARL](https://earl.eanm.org/) protocol.

However, there are only a handful of tools to obtain the RCs from the PET images of the phantoms. The community still needs yet another tool to build their pipelines.

In light of this, I developed a personal pipeline, emulating the EARL protocol, to perform harmonization evaluations. I have already applied this protocol in multiple healthcare providers in Beijing.

I hope you enjoy the project and the tool.

## References

- Boellaard, Ronald, et al. ["FDG PET and PET/CT: EANM procedure guidelines for tumour PET imaging: version 1.0."](https://link.springer.com/article/10.1007/s00259-009-1297-4) European Journal of Nuclear Medicine and Molecular Imaging 37 (2010): 181-200.
  > EANM guidelines 1.0, which proposed the original version of the EARL protocol, EARL1.
- Kaalep, Andres, et al. ["Feasibility of state of the art PET/CT systems performance harmonisation."](https://link.springer.com/article/10.1007/s00259-018-3977-4) European Journal of Nuclear Medicine and Molecular Imaging 45 (2018): 1344-1361.
  > Proposed the range for EARL2.
- Siemens [EQ•PET](https://www.siemens-healthineers.com/perspectives/mso-harmonizing-suv-with-eqpet.html), with [white paper](https://www.siemens-healthineers.com/en-us/molecular-imaging/eq-pet-thank-you).
  > Siemens released a product to perform harmonizations over different scanners. The principles are similar, but the purpose of *BCH EARL* is not the same.
- Tsutsui, Yuji, et al. ["Multicentre analysis of PET SUV using vendor-neutral software: the Japanese Harmonization Technology (J-Hart) study."](https://ejnmmires.springeropen.com/articles/10.1186/s13550-018-0438-9) EJNMMI Research 8 (2018): 83.
  > Another similar protocol practiced in Japan.

## License

For now, I am reserving all rights. But I do have a plan to release it as an open source software. However, I also retain the rights of commercialization.

## Cite

Please [contact](#contact) me before my paper gets published. Thank you in advance.

## Contact

See my [homepage](https://mengxiangxi.info/). I am very happy to discuss with you about it.

## History

Release history of the *BCH EARL* tool.

| Version | Date | Comment |
| --- | --- | --- |
| 0.1 | 20220709 | First Release |
| 0.5.0 | 20230721 | Final evaluation version |

## Acknowledgement

Thank you for reviewing the code and/or testing the functions.

- Jingjing Li, United Imaging Healthcare, Shanghai
- Yifan Wu, United Imaging Healthcare, Shanghai
- Debin Hu, Nanfang Hospital, Southern Medical University, Guangzhou

This project is support by the following agencies

- National Key R&D Program of China (2022YFC2409405), Ministry of Science and Technology of the People's Republic of China 
- Beijing Center for Nuclear Medicine Quality Control and Improvement, Beijing Cancer Hospital
