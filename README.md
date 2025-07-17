# Shopping Cart Management System

This is a JavaFX-based Shopping Cart Management System developed as part of a group project. It simulates key functionalities of an e-commerce platform including user authentication, product browsing, cart management, and order processing.


## 📁 Project Structure

Group Project/
├── GUI-wireframe.drawio # Wireframe design (Draw.io)
├── Shopping_cart_manage_system_flow_map.drawio # System flow diagram
├── Shopping_cart_manage_system_flow_map.drawio.pdf
├── Shopping_Cart_Management_system/
│ └── ShoppingCart/
│ ├── .git/ # Git version control (if applicable)
│ ├── .classpath / .project # Eclipse metadata
│ ├── pom.xml # Maven config file
│ ├── *.ser # Serialized data structures (e.g., cart.ser)
│ ├── products.csv # Product list
│ ├── Queue.csv # Queue data
│ ├── users.txt / otps.txt # Login data
│ └── build.fxbuild # JavaFX build file


---

## Features

- **Product Management**  
  Load and manage products using `products.csv`.

- **User Login & OTP**  
  Simple authentication using `users.txt` and `otps.txt`.

- **Cart & Queue System**  
  Add/remove products, simulate queues, stacks, and AVL trees via serialization.

- **JavaFX GUI**  
  Interactive graphical interface built with JavaFX.

- **Flow Map & Wireframes**  
  System flow and GUI design included via `.drawio` and `.pdf`.


## Technologies Used

- **Java 11+**
- **JavaFX**
- **Maven** (via `pom.xml`)
- **Serialized Java Objects (`.ser`)**
- **CSV files**
- **Draw.io** (for diagrams)

---

## Diagrams

- `GUI-wireframe.drawio` — GUI wireframe
- `Shopping_cart_manage_system_flow_map.drawio/pdf` — System architecture

You can open `.drawio` files using [https://app.diagrams.net](https://app.diagrams.net) or import into compatible IDEs.

---

## How to Run

```bash
1. Clone the repository
git clone https://github.com/yourusername/shopping-cart-system.git
cd shopping-cart-system

2. Open in your IDE (Eclipse/IntelliJ)
Import it as a Maven Project.

3. Build the project

mvn clean install

4. Run the application
Make sure you have JavaFX SDK configured. Run:

java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -jar target/ShoppingCart.jar
Replace /path/to/javafx-sdk/lib with the actual path to your JavaFX SDK.

Contributors:
Developed by a passionate group of students as part of a university project.

Jahmari Harrison
Daniel Morris
Tyrese Dunbar
Shemael Deslandes
Andre


## License
This project is created for academic purposes only.
