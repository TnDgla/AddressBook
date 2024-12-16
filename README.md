### Address Book Web App

#### **Overview**
The Address Book Web App is a CRUD (Create, Read, Update, Delete) application developed using Angular for the frontend and Angular Material for styling. It provides functionalities to manage contact information, including creating, reading, updating, and deleting contacts. The project is responsive and includes features like a navigation menu and a dialog for editing or deleting contacts.

---

### **Mission and Objectives**

#### **Goal:**
By the end of this project, participants will have a fully functional Address Book application with a professional and user-friendly interface.

#### **Objectives:**
1. Implement CRUD operations for managing contacts.
2. Use Angular Material for responsive UI components.
3. Create and integrate services for data management.
4. Implement form validation and dialog-based interactions.

---

### **Technology Stack**

#### **Frontend**
1. **Angular**
   - **Why?**: Framework for building dynamic web applications.
   - **Use Cases**: Component-based architecture for managing views and forms.

2. **Angular Material**
   - **Why?**: Provides pre-designed UI components.
   - **Use Cases**: Buttons, tables, dialogs, and responsive design.

#### **Development Tools**
1. **Visual Studio Code**
   - **Why?**: IDE for writing, debugging, and managing Angular code.

2. **Node.js**
   - **Why?**: Used for package management and running Angular CLI.

3. **Git**
   - **Why?**: Version control for managing project files.

---

### **Workflow Overview**

The Address Book Web App workflow ensures seamless interactions between the user and the application’s features, following a well-defined flow:

1. **User Actions**: 
   - Users can view, create, edit, or delete contacts.
   - Dialogs are used to confirm or input contact information.

2. **Frontend**: Angular components and services handle user interactions and communicate with the backend via HTTP requests.

3. **Backend**: Data is managed using Angular services, simulating or integrating with a database for storing and retrieving contacts.

4. **UI/UX**: Responsive Angular Material components provide a consistent and user-friendly interface.

---

### **System Architecture**

The system architecture of the Address Book Web App is structured to ensure modularity, scalability, and responsiveness:

- **Frontend**: 
  - Angular for managing components and routing.
  - Angular Material for UI components.

- **Backend (Simulated)**: 
  - Angular services to handle data and simulate backend logic.

- **Storage**:
  - Contacts data managed in-memory or integrated with a database in a future enhancement.
 
![image](https://github.com/user-attachments/assets/7e5aa273-0325-40b0-9fdf-50d306f6e724)


---

### **Project Structure for Feature Implementation**

This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

NOTE: Participants are encouraged to customize the design and functionality to make the application unique.

---

### **Week-by-Week Implementation**

#### **Week 1: Setup and Basic Structure**
**Tasks:**
1. Install Angular CLI and create a new Angular project.
   - Command: `npx @angular/cli new address-book`

   **Reading Material:**  
   - [Angular CLI Documentation](https://angular.io/cli)  
   - [Node.js Installation Guide](https://nodejs.org/en/download/)

   **Video Tutorial:**  
   - [Angular Setup Guide](https://www.youtube.com/watch?v=3qBXWUpoPHo)

2. Set up Angular Material.
   - Command: `ng add @angular/material`

   **Reading Material:**  
   - [Angular Material Setup](https://material.angular.io/guide/getting-started)

   **Video Tutorial:**  
   - [Angular Material Setup Guide](https://www.youtube.com/watch?v=KhzGSHNhnbI)

3. Create project folders: `components`, `services`, `dialogs`.

**Deliverables:**
- Angular project with basic folder structure.
- Angular Material installed and configured.

---

#### **Week 2: Display Contacts**
**Tasks:**
1. Create a `ContactsService` to manage contact data.
   - Command: `ng generate service services/contacts`

   **Reading Material:**  
   - [Angular Services](https://angular.io/guide/architecture-services)

   **Video Tutorial:**  
   - [Angular Service Creation Guide](https://www.youtube.com/watch?v=t8SZv8_7Rlc)

2. Use Angular Material Table to display contact information.
   - Import: `MatTableModule`.

   **Reading Material:**  
   - [Angular Material Table](https://material.angular.io/components/table/overview)

   **Video Tutorial:**  
   - [Angular Material Table Guide](https://www.youtube.com/watch?v=6fw7eHDxzE0)

3. Fetch mock data from `ContactsService` and bind it to the table.

   **Reading Material:**  
   - [Fetching Data in Angular](https://angular.io/guide/http)

   **Video Tutorial:**  
   - [Angular HTTPClient Basics](https://www.youtube.com/watch?v=bkACi-A5Rkw)

**Deliverables:**
- Functional contact table displaying mock data.
- Service for managing contact data.

---

#### **Week 3: Add and Update Contacts**
**Tasks:**
1. Create a form for adding a new contact using Angular Material.
   - Import: `MatFormFieldModule`, `ReactiveFormsModule`.

   **Reading Material:**  
   - [Angular Reactive Forms](https://angular.io/guide/reactive-forms)

   **Video Tutorial:**  
   - [Angular Reactive Forms Tutorial](https://www.youtube.com/watch?v=EcRFYF4B3IQ)

2. Implement validation rules using Angular Reactive Forms.

   **Reading Material:**  
   - [Form Validation in Angular](https://angular.io/guide/form-validation)

   **Video Tutorial:**  
   - [Angular Form Validation](https://www.youtube.com/watch?v=BrnDLHPIHoY)

3. Add dialogs for editing contact information.

   **Reading Material:**  
   - [Angular Material Dialog](https://material.angular.io/components/dialog/overview)

   **Video Tutorial:**  
   - [Angular Dialog Example](https://www.youtube.com/watch?v=8uDJ-xrvAkI)

**Deliverables:**
- Form for adding and editing contacts.
- Dialog-based interface for updating contacts.

---

#### **Week 4: Delete Contacts and Finalize UI**
**Tasks:**
1. Implement delete functionality using Angular Material Dialog.

   **Reading Material:**  
   - [Angular Material Dialog](https://material.angular.io/components/dialog/overview)

   **Video Tutorial:**  
   - [Angular Delete Dialog Example](https://www.youtube.com/watch?v=06-Hhcr54xI)

2. Add animations for dialogs and table rows.

   **Reading Material:**  
   - [Angular Animations](https://angular.io/guide/animations)

   **Video Tutorial:**  
   - [Angular Animation Guide](https://www.youtube.com/watch?v=hsE6UyFIC4g)

3. Finalize responsive UI with Angular Material breakpoints.

   **Reading Material:**  
   - [Angular Material Breakpoints](https://material.angular.io/cdk/layout/overview)

   **Video Tutorial:**  
   - [Angular Responsive Design](https://www.youtube.com/watch?v=hNgr8j3h0JA)

**Deliverables:**
- Functional delete button with confirmation dialogs.
- Responsive and polished UI.

---
### **Screenshots**

![Screenshot (254)](https://github.com/user-attachments/assets/4f8b5241-d342-4a9a-926f-11708e651a3b)
![Screenshot (249)](https://github.com/user-attachments/assets/ddc625d4-caea-458c-9ce0-bc46ba5f6e0e)
![Screenshot (250)](https://github.com/user-attachments/assets/14ff038f-04c6-41bc-9b7c-68a6183a7c35)
![Screenshot (251)](https://github.com/user-attachments/assets/e925b389-0efd-4bbd-a62e-c23e6bde9d12)
![Screenshot (252)](https://github.com/user-attachments/assets/b3f348e3-d4b9-420b-b29a-71c43672da54)
![Screenshot (253)](https://github.com/user-attachments/assets/1983216e-f109-4cc8-9fed-f9be5e143d05)


### **References**
- [Angular Documentation](https://angular.io/docs)
- [Angular Material Documentation](https://material.angular.io/)
- [GitHub Repository for Address Book App](https://github.com/user/address-book)
- https://www.youtube.com/watch?v=cobsEPQb2jk
- https://github.com/katkovd73/Address-Book-Angular-Project-Full-CRUD



