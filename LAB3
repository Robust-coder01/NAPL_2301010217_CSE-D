package main

import (
	"fmt"
)

type person struct {
	name   string
	age    int
	job    string
	salary float64
}

func (p *person) readData() {
	fmt.Println("Enter name:")
	fmt.Scanln(&p.name)
	fmt.Println("Enter age:")
	fmt.Scanln(&p.age)
	fmt.Println("Enter job:")
	fmt.Scanln(&p.job)
	fmt.Println("Enter salary:")
	fmt.Scanln(&p.salary)
}

func (p *person) printData() {
	fmt.Println("\n----formatted person data-----")
	fmt.Println("Name:", p.name)
	fmt.Println("Age:", p.age)
	fmt.Println("Job:", p.job)
	fmt.Println("Salary:", p.salary)
}

func main() {
	var p1, p2 person

	fmt.Println("Enter details for person 1:")
	p1.readData()
	p1.printData()

	fmt.Println("Enter details for person 2:")
	p2.readData()
	p2.printData()
}
