struct Student {
    name: String,
    email: String,
    phno: String,
    id: i32,
}

fn main() {
    let mut students: Vec<Student> = Vec::new();

    students.push(Student {
        name: "John Doe".to_string(),
        email: "johndoe@example.com".to_string(),
        phno: "1234567890".to_string(),
        id: 1,
    });

    students.push(Student {
        name: "Jane Doe".to_string(),
        email: "janedoe@example.com".to_string(),
        phno: "9876543210".to_string(),
        id: 2,
    });

    students.push(Student {
        name: "Peter Smith".to_string(),
        email: "petersmith@example.com".to_string(),
        phno: "0987654321".to_string(),
        id: 3,
    });

    students.push(Student {
        name: "Mary Johnson".to_string(),
        email: "maryjohnson@example.com".to_string(),
        phno: "1987654320".to_string(),
        id: 4,
    });

    students.push(Student {
        name: "David Williams".to_string(),
        email: "davidwilliams@example.com".to_string(),
        phno: "1876543219".to_string(),
        id: 5,
    });

    let index = 10; // Out of bounds index

    let student = match students.get(index) {
        Some(student) => student,
        None => panic!("Student with index {} not found", index),
    };

    println!("Name: {}", student.name);
    println!("Email: {}", student.email);
    println!("Phone: {}", student.phno);
    println!("ID: {}", student.id);
}

