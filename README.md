# Verilock

This repository includes the artifacts for the ASPLOS 2024 submission #161. `Verilock.jar` is the executable jar of Verilock. `cases` folder includes the cases collected from the previous literature and automatically synthesized asynchronous circuits.

## Reproducing experimental results

1. Clone this repository.

2. Navigate to the project directory.

   ```bash
   cd Verilock
   ```

3. Install OpenJDK 20.

4. Run the first experiment with the following command.

   ```java
   java --enable-preview -jar Verilock.jar RQ1
   ```

5. Run the second experiment with the following command.

   ```java
   java --enable-preview -jar Verilock.jar RQ2
   ```

   

