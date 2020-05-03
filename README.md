#FXDiagram binaries

---

This repository has been created for convenience developing application using Jan Koehnlein's _FXDiagram_ project.
It contains packaged jars for standalone application creating (outside of eclipse).
Unfortunately those jars lacks source information and **are not** present at **Maven**.

##Usage

In order to use both packaged jars and sources you need to download sources from the next repositories:
- git@github.com:JanKoehnlein/FXDiagram.git
- git@github.com:JanKoehnlein/JavaFX-SWT-Gesture-Bridge.git
- git@github.com:JanKoehnlein/fxdiagram-xtext-examples.git (I guess it is not related to standalone project);
- https://git.rtsys.informatik.uni-kiel.de/scm/kieler/pragmatics.git (is used for autolayout features)

##Dependencies

In order to develop your own standalone JavaFX application with FXDiagram you need to manually include the following jars to your classpath:
* All the de.cau.cs.kieler-* jars (used for autolayout);
* de.fxdiagram.core-{version}-SNAPSHOT.jar;
* de.fxdiagram.external-{version}-SNAPSHOT.jar
* de.fxdiagram.lib-{version}-SNAPSHOT.jar
* de.fxdiagram.noeclipse-{version}-SNAPSHOT.jar;
* de.fxdiagram.mapping-{version}-SNAPSHOT.jar (if you are going to leverage FXDiagram model mapping feature

Currently the only version uploaded is 0.35.1-SNAPSHOT.