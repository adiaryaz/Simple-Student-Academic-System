# Simple Student Academic System

A console-based application to manage student records using Python lists and dictionaries.

## 📝 Description

This program functions as a simple Academic System for students. It allows users to perform basic CRUD (Create, Read, Delete) operations on a database of students. The data is stored in a list of dictionaries, where each dictionary represents a student profile containing their Name, Age, and Study Program (Prodi). The program initializes with two default students (Budi and Asep).

-----

## 🎯 Problem Statement

### Input:

  * **Menu Selection:** An integer (1-4) to navigate the main menu.
  * **Student Data:**
      * Name (String)
      * Age (Integer)
      * Study Program/Prodi (String)
  * **Navigation:** An integer (1 or 2) to return to the main menu or exit specific functions.
  * **Deletion:** An integer representing the index of the student to be removed.

### Output:

  * A formatted list of students showing Index, Name, Age, and Prodi.
  * Success messages upon adding or deleting a student.
  * Interactive menu prompts.

### Rules:

1.  **Data Structure:** Student data must be stored in a dictionary format: `{'name': ..., 'umur': ..., 'prodi': ...}` and collected within a main list.
2.  **Menu Options:**
      * **1:** Display all students currently in the list.
      * **2:** Add a new student by inputting their details.
      * **3:** Delete a student based on their displayed index.
      * **4:** Exit the program (though not explicitly defined in the provided code logic, it is listed in the print statement).
3.  **Indexing:** Deletion is performed based on the **0-based index** displayed in the "Show List" view.
4.  **Navigation:** After an operation, the user must select '1' to return to the main menu to continue operations.

-----

## 💡 Examples

### Example 1 (Viewing Data)

**Input:**

```text
Pilih Menu: 1
```

**Output:**

```text
Index: 0
Nama Mahasiswa: Budi
Umur : 20
Prodi: Sistem Informasi

Index: 1
Nama Mahasiswa: Asep
Umur : 21
Prodi: Ilmu Komputer
```

**Explanation:** The user selects option 1, and the program iterates through the list to display the default data.

### Example 2 (Adding Data)

**Input:**

```text
Pilih Menu: 2
Input Nama Mahasiswa: Caca
Input Umur Mahasiswa: 19
Input Prodi Mahasiswa: DKV
```

**Output:**

```text
Data Mahasiswa Berhasil di Tambah!!
```

**Explanation:** The user adds a new student. This new dictionary is appended to the main list.

### Example 3 (Deleting Data)

**Input:**

```text
Pilih Menu: 3
(Displays list...)
Input Index Mahasiswa: 0
```

**Output:**

```text
Data Mahasiswa Berhasil di Hapus!!
```

**Explanation:** The user selects option 3, views the list, and chooses index 0. The student "Budi" is removed from the list.

-----

## 🚀 How to Use

1.  **Clone this repository**

    ```bash
    git clone https://github.com/adiaryaz/student-academic-system.git
    cd student-academic-system
    ```

2.  **Run the program** (assuming the file is `List Mahasiswa.py`):

    ```bash
    python "List Mahasiswa.py"
    ```

    Follow the on-screen menu prompts to manage student data.
