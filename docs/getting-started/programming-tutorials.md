# Programming Tutorials 💻

Welcome to the programming section!  
These tutorials will help you understand how our robot code works, and how to contribute new features confidently.

---

## 🚦 Command-Based Programming

FRC Java projects use the **Command-Based architecture**.  
In this design:

- Each **Subsystem** controls one robot mechanism (like drivetrain, shooter, intake)
- **Commands** tell those subsystems what to do
- **Triggers/Buttons** map operator inputs to commands

### 📘 Learn More
- [WPILib Command-Based Overview](https://docs.wpilib.org/en/stable/docs/software/commandbased/index.html)
- [What Is Command-Based Programming?](https://docs.wpilib.org/en/stable/docs/software/commandbased/what-is-command-based.html)
- [Creating Commands and Subsystems](https://docs.wpilib.org/en/stable/docs/software/commandbased/commands.html)

---

## 🧠 Java Basics Refresher

If you’re new to programming, start with some quick Java learning:

- [W3Schools Java Tutorial](https://www.w3schools.com/java/)
- [Codecademy Java Track](https://www.codecademy.com/learn/learn-java)
- [Bro Code YouTube: Java Crash Course](https://www.youtube.com/watch?v=xk4_1vDrzzo)

Focus on:

- Classes and methods  
- Object-oriented concepts (inheritance, encapsulation)  
- Control structures (`if`, `for`, `while`)  
- Using constructors and parameters

---

## 🔩 FRC Code Anatomy

A typical robot project (`src/main/java/frc/robot/`) includes:

- Robot.java → Main entry point
- Constants.java → Port numbers and tuning constants 
- subsystems/ → Code for each mechanism (drivetrain, intake, etc.)
- commands/ → Autonomous and teleop actions
- RobotContainer.java → Connects inputs to commands

### Example Command

```java

public class DriveCommand extends CommandBase {
    private final Drivetrain drivetrain;
    private final Joystick joystick;

    public DriveCommand(Drivetrain drivetrain, Joystick joystick) {
        this.drivetrain = drivetrain;
        this.joystick = joystick;
        addRequirements(drivetrain);
    }

    @Override
    public void execute() {
        drivetrain.arcadeDrive(joystick.getY(), joystick.getX());
    }
}
```