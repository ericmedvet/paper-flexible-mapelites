# paper-flexible-mapelites
Software artifacts related to an improvement of the MapElites optimization algorithm dealing with the **structure of the archive holding solutions**.

It allows you to reproduce the experimental results presented in the paper, including all reported figures.



## How to reproduce the experiments

### Requirements
- JDK 25
- Maven 
- Git
- JGEA 2.8.2 (*not yet available in stable version, use the snapshot*)

For the latter, you can obtain the executable artifact `jgea.jar` (the only artifact you need) this way.
First, clone and build it:
```bash
git clone --branch v2.8.2 https://github.com/ericmedvet/jgea.git
cd jgea
mvn clean package -U
```

Then, copy the `.jar` in this directory (assuming you put jgea in `../jgea`): 
```bash
cp ../jgea/io.github.ericmedvet.jgea.experimenter/target/jgea.jar .
```
