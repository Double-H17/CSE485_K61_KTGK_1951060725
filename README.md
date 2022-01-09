# CSE485_K61_KTGK_1951060725
<?php
     require_once 'configs/db.php';

     class EmployeeModel{
         private $employeeId;
         private $employeeName;

         public function index(){
             $connection = $this -> connectDb;
             //truy van du lieu
             $querySelect = "SELECT * FROM nhanvien";

            
         }
