Semantic Body Illustrations
===========================

<p align="center">
  <img src="http://sbb.cellfinder.org/github.svg"
       alt="Semantic Body Illustrations" />
</p>

A set of semantically annotated illustrations of the human and mouse body
featuring the liver and kidney. The illutrations have been created in for the
[Semantic Body Browser][sbb] - a tool for graphically exploring an organism's
body. (Lekschas *et al.*)


Annotation
----------

Illustrations are ontologically annotated using [RDFa 1.1][rdfa]. There are two
annotation schemes available:

1. Species-specific ontologies, e.g. [Foundational Model of Anatomy (FMA)][fma]
   for homo sapiens and [Mouse Adult Gross Anatomy (MA)][ma] ontology for mus
   musculus.
2. Cross-species ontology [Uberon][uberon] in combination with
   [NCBI taxon][ncbitaxon].

Choose the one, which suites you best.

In general illustrations are annotated according to the following scheme:

Species: NCBI Taxon (2)
Organs and tissues: [FMA][fma] / [MA][ma] (1) or [UBERON][uberon] (2)
Cells: [CL][cl]
Sub-cellular components: [GO][go] and [BT][bt]
Anything else: [CELDA][celda]


Minimize
--------
If you are planning to use the illustrations in your web application I recommend optimizing the file size with [svgo][svgo]. You can use our script like so:

`$ optimize <directory>`

E.g. `directory` could be `homo-sapiens`. For details regarding the script see `$ optimize -h` and regarding `svgo` please have a look at its [project page][svgo].


Contributions
-------------

You like to contribute? Great! Please [request a pull][pull] and add yourself to
the list of licenses below.


Issues
------

If you find any issues please be so kind and report them [here][issues] and we
swear to fix them as soon as possible.


License
-------

| Illustration                       | Attribution        | Adaptation      | License                 |
| ---------------------------------- | ------------------ | --------------- | ----------------------- |
| Adult Collecting Duct<sup>*</sup>  | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Distal Tubule<sup>*</sup>    | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Gall Bladder<sup>*</sup>     | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Hepatic Acinus<sup>*</sup>   | Frevert et al.     | Lekschas et al. | [CC BY-SA 4.0][ccbysa4] |
| Adult Hepatic Lobes<sup>*</sup>    | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Hepatic Lobules<sup>*</sup>  | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Hepatocyte<sup>*</sup>       | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Kidney<sup>*</sup>           | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Nephron<sup>*</sup>          | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Podocyte<sup>*</sup>         | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Proximal Tubule<sup>*</sup>  | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Renal Corpuscle<sup>*</sup>  | Michal Komorniczak | Lekschas et al. | [CC BY-SA 3.0][ccbysa3] |
| Adult Renal Lobe<sup>*</sup>       | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Adult Ureter<sup>*</sup>           | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Capillary Loop Nephron<sup>*</sup> | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Comma-Shaped Body<sup>*</sup>      | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Human Adult Female Body            | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Human Adult Male Body              | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Mouse Adult Body                   | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Mouse Adult Liver                  | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Pretubular Aggregate<sup>*</sup>   | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| Renal Vesicle<sup>*</sup>          | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |
| S-Shaped Body<sup>*</sup>          | Lekschas et al.    |                 | [CC BY-SA 4.0][ccbysa4] |

<sup>*</sup> Same for human and mouse illustration.


[bt]: http://bioportal.bioontology.org/ontologies/BT "BioTop Ontology"
[ccbysa3]: https://creativecommons.org/licenses/by-sa/3.0/
[ccbysa4]: https://creativecommons.org/licenses/by-sa/4.0/
[celda]: http://cellfinder.org/about/ontology/ "Cell Expression Localization Development Anatomy Ontology"
[cl]: http://bioportal.bioontology.org/ontologies/CL "Cell Ontology"
[fma]: http://bioportal.bioontology.org/ontologies/FMA "Foundational Model of Anatomy Ontology"
[go]: http://bioportal.bioontology.org/ontologies/GO "Gene Ontology"
[issues]: https://github.com/flekschas/sbi/issues "File an issues"
[ma]: http://bioportal.bioontology.org/ontologies/MA "Mouse Gross Anatomy Ontology"
[ncbitaxon]: http://bioportal.bioontology.org/ontologies/NCBITAXON "NCBI Organismal Classification"
[pull]: https://github.com/flekschas/sbi/pulls
[rdfa]: http://www.w3.org/TR/rdfa-syntax/ "RDF in Attributes"
[sbb]: http://sbb.cellfinder.org "Semantic Body Browser"
[svgo]: https://github.com/svg/svgo "SVG Optimizer"
[uberon]: http://bioportal.bioontology.org/ontologies/UBERON "Uber Anatomy Ontology"
