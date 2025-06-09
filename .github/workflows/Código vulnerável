public class Vulnerable {
    public static void main(String[] args) throws Exception {
        String userInput = args[0];
        String query = "SELECT * FROM users WHERE name = '" + userInput + "'";
        java.sql.Connection con = java.sql.DriverManager.getConnection("jdbc:mysql://localhost/test", "root", "");
        java.sql.Statement stmt = con.createStatement();
        java.sql.ResultSet rs = stmt.executeQuery(query);
    }
}
