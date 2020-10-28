package com.app.main;

import com.app.dao.EmployeeDAO;
import com.app.exception.BusinessException;
import com.app.model.Employee;

public class Main {

	public static void main(String[] args) {
	
		EmployeeDAO dao=new EmployeeDAO();
		Employee emp=new Employee(105, "Nagammal", 26, 123455.66, 9123456789L);
		try {
			int c=dao.createEmployee(emp);
			if(c>0) {
				System.out.println("Employee registered successfullyy");
			}
		} catch (BusinessException e) {
			System.out.println(e.getMessage());
		}

	}

}
