# Test My progect Gethup
testWorke

this project to lern get
CREATE TABLE dbo.tbl_DesginCertificateModelPlan_num(
	ID int IDENTITY(1,1) NOT FOR REPLICATION NOT NULL,
	Model_ID int NULL,
	Plan_num int NULL, 
	gender int NULL,
   Model_PlanType int NULL, 
	Foundation int NULL,
	statusplan int NULL  DEFAULT(1),
	userid int NULL,
	Datefrom nvarchar(20) NULL,
	DateTO nvarchar(20) NULL, 
	 DefaultDateAdd_M datetime NULL  DEFAULT (getdate()) ,
	DefaultDateAdd_H nvarchar(50) NULL    DEFAULT (format(getdate(),'yyyy/MM/dd','ar')) ,
 )   ON [PRIMARY]
  
