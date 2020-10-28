package com.app.dbutil;

import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.SQLException;

public class MySqlConnection {

	private static Connection connection;
	
	public static Connection getConnection() throws ClassNotFoundException, SQLException {
		Class.forName("com.mysql.cj.jdbc.Driver");
		System.out.println("Driver Loaded successfully");
		String url="jdbc:mysql://localhost:3306/tvs";
		String username="root";
		String password="root";
		connection=DriverManager.getConnection(url, username, password);
		return connection;
	}
}
//SingleTon Java Class - only and only one instance/object of this class will be maintained throughout the application