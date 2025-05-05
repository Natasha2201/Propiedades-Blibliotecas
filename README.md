# 📦 Propiedades y Bibliotecas - Windows Forms + Clase Biblioteca

Este proyecto está compuesto por dos partes: una clase de biblioteca (`Producto`) y una **aplicación Windows Forms** que permite al usuario ingresar y mostrar información sobre un producto.

---

## 🧱 Estructura del Proyecto

- 📚 **BibliotecaEjemplo**  
  Contiene la clase `Producto` con propiedades y métodos encapsulados.

- 🖥️ **AppFormEjemplo**  
  Aplicación de escritorio (Windows Forms) que interactúa con el usuario para mostrar los datos del producto.

---

## 🚀 Funcionalidades

- 📝 Ingresar el nombre y precio de un producto
- 📄 Mostrar la descripción del producto con formato de moneda
- ❌ Validación para evitar entradas no numéricas en el precio
- 🔔 Mensaje de error si el precio ingresado no es válido

---

## 🧩 Componentes del formulario

- `txtNombre`: Caja de texto para ingresar el nombre del producto  
- `txtPrecio`: Caja de texto para ingresar el precio  
- `btnMostrar`: Botón para mostrar los datos del producto  
- `lblResultado`: Etiqueta donde se muestra la descripción del producto  

---

## 🧠 Clase `Producto`

```csharp
public string ObtenerDescripcion()
{
    return $"Producto: {Nombre}, Precio: {Precio:C}";
}
