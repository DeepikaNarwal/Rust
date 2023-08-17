fn main() {
    let mut num1: i32 = 10;
    let mut num2: i32 = 20;

    println!("Numbers before calculation: \nnum1:{}\nnum2:{}", num1, num2);

    // Addition
    let sum = add_numbers(&mut num1, &mut num2);
    println!("The sum is: {}", sum);

    // Subtraction
    let difference = subtract_numbers(&mut num1, &mut num2);
    println!("The difference is: {}", difference);

    // Multiplication
    let product = multiply_numbers(&mut num1, &mut num2);
    println!("The product is: {}", product);

    // Division
    let quotient = divide_numbers(&mut num1, &mut num2);
    println!("The quotient is: {}", quotient);
}

fn add_numbers(num1: &mut i32, num2: &mut i32) -> i32 {
    *num1 += *num2;
    return *num1;
}

fn subtract_numbers(num1: &mut i32, num2: &mut i32) -> i32 {
    *num1 -= *num2;
    return *num1;
}

fn multiply_numbers(num1: &mut i32, num2: &mut i32) -> i32 {
    *num1 *= *num2;
    return *num1;
}

fn divide_numbers(num1: &mut i32, num2: &mut i32) -> i32 {
    *num1 /= *num2;
    return *num1;
}
