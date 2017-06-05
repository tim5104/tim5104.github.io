<?php require_once('Connections/member.php'); ?>

<?php  //開啟SESSION與設定UTF8語系
	session_start(); 
	mysql_query("set names 'utf8'");
?>

<?php //清瀏覽器緩存資料
header("Last-Modified: " . gmdate( "D, d M Y H:i:s" ) . "GMT" );  
header("Cache-Control: no-cache, must-revalidate" );  
?>

<?php

// ** Logout the current user. **
$logoutAction = $_SERVER['PHP_SELF']."?doLogout=true";
if ((isset($_SERVER['QUERY_STRING'])) && ($_SERVER['QUERY_STRING'] != "")){
  $logoutAction .="&". htmlentities($_SERVER['QUERY_STRING']);
}

if ((isset($_GET['doLogout'])) &&($_GET['doLogout']=="true")){
  //to fully log out a visitor we need to clear the session varialbles
  $_SESSION['MM_Username'] = NULL;
  $_SESSION['MM_UserGroup'] = NULL;
  $_SESSION['PrevUrl'] = NULL;
  unset($_SESSION['MM_Username']);
  unset($_SESSION['MM_UserGroup']);
  unset($_SESSION['PrevUrl']);
	
  $logoutGoTo = "index.php";
  if ($logoutGoTo) {
    header("Location: $logoutGoTo");
    exit;
  }
}
?>
<?php
if (!function_exists("GetSQLValueString")) {
function GetSQLValueString($theValue, $theType, $theDefinedValue = "", $theNotDefinedValue = "") 
{
  if (PHP_VERSION < 6) {
    $theValue = get_magic_quotes_gpc() ? stripslashes($theValue) : $theValue;
  }

  $theValue = function_exists("mysql_real_escape_string") ? mysql_real_escape_string($theValue) : mysql_escape_string($theValue);

  switch ($theType) {
    case "text":
      $theValue = ($theValue != "") ? "'" . $theValue . "'" : "NULL";
      break;    
    case "long":
    case "int":
      $theValue = ($theValue != "") ? intval($theValue) : "NULL";
      break;
    case "double":
      $theValue = ($theValue != "") ? doubleval($theValue) : "NULL";
      break;
    case "date":
      $theValue = ($theValue != "") ? "'" . $theValue . "'" : "NULL";
      break;
    case "defined":
      $theValue = ($theValue != "") ? $theDefinedValue : $theNotDefinedValue;
      break;
  }
  return $theValue;
}
}

$colname_Recordset1 = "-1";
if (isset($_SESSION['MM_Username'])) {
  $colname_Recordset1 = $_SESSION['MM_Username'];
}
mysql_select_db($database_member, $member);
$query_Recordset1 = sprintf("SELECT * FROM member_data WHERE phone = %s", GetSQLValueString($colname_Recordset1, "int"));
$Recordset1 = mysql_query($query_Recordset1, $member) or die(mysql_error());
$row_Recordset1 = mysql_fetch_assoc($Recordset1);
$totalRows_Recordset1 = mysql_num_rows($Recordset1);

$colname_Recordset2 = "-1";
if (isset($_SESSION['MM_Username'])) {
  $colname_Recordset2 = $_SESSION['MM_Username'];
}
mysql_select_db($database_member, $member);
$query_Recordset2 = sprintf("SELECT phone, filename FROM member_image WHERE phone = %s", GetSQLValueString($colname_Recordset2, "int"));
$Recordset2 = mysql_query($query_Recordset2, $member) or die(mysql_error());
$row_Recordset2 = mysql_fetch_assoc($Recordset2);
$totalRows_Recordset2 = mysql_num_rows($Recordset2);
?>

<!DOCTYPE html> 
<html>
<head>

	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="msapplication-TileImage" content=""/>    

<title>Android.Sport</title>
	
    <!--<link rel="SHORTCUT ICON" href=""><!--網頁圖示-->
    
    <link href="jquery-mobile/123.min.css" rel="stylesheet" type="text/css" />
    <link href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css" rel="stylesheet"  />
    
	<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
    <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
    
    <link href="jquery-mobile/index_3d_menu.css" rel="stylesheet" />
    <script src="jquery-mobile/index_3d_menu.js"></script>
    
	<style type="text/css">
    tr { 
      border-bottom:1px solid #000; 
    }
    </style>
    

</head> 

<body>


<?php  if(isset($_SESSION['MM_Username'])) { ?> <!--已登入狀態-->

<div id="index" data-role="page" >
    
    
	  <div id="header" data-position="fixed" data-role="header" data-theme="b">
                <a class="ui-btn ui-btn-left ui-btn-icon-left ui-icon-bars" 
                    					href="#menu" style="padding: 15px; background: none;"></a>
                <h1>Android.Sport</h1>
    </div>
            
	
    <div >
        <ul data-role="listview" data-divider-theme="a">
            <li><a href="http://tw.mobi.yahoo.com" data-ajax="false" data-prefetch="true">壓虎123</a></li>
            <li><a href="http://www.google.com" data-ajax="false" data-prefetch="true">股歌</a></li>
            
        </ul>
    </div>
    
        <!--SideMenu-->
    <div id="menu" data-role="panel" data-position="left" data-display="overlay">
        
        <table align="center" width="100%" >
        
          <tr style="border-bottom:1px solid #000;">
            
            	<h5 align="center">您好，<?php echo $row_Recordset1['name']; ?></h5>
            	<!--<img src="image/upload/user/<?php echo $row_Recordset2['filename']; ?>" width="100"> -->    

          </tr>
          
          <tr>
            <th scope="row">&nbsp;</th>
          </tr>
                   
          <tr>
            <th scope="row">
            	<font color="#0099FF" size="+2">尋找夥伴</font>
            </th>
          </tr>
          
          <tr>
            <th scope="row" >
            	<a href="find_partner_now.php" class="ui-btn" data-ajax="false">
		            目前組隊
                </a>
            </th>
          </tr>
          
          <tr>
            <th scope="row">
            	<a href="find_partner_add.php" class="ui-btn" data-ajax="false">
					新增組隊
                </a>
            </th>
          </tr>
          
          <tr>
            <th scope="row">
            	<a href="find_partner_myself.php" class="ui-btn" data-ajax="false">
                	我的組隊
                </a>
             </th>
          </tr>
          
          <tr>
            <th scope="row">&nbsp;</th>
          </tr>
          
          <tr>
            <th scope="row">
            	<font color="#0099FF" size="+2">活動快訊</font>
            </th>
          </tr>
          
          <tr>
            <th scope="row" >
            	<a href="activities_news_1.php" class="ui-btn" data-ajax="false">
                	目前活動
                </a>
            </th>
          </tr>
          
          <tr>
            <th scope="row" >
            	<a href="activities_news_2.php" class="ui-btn" data-ajax="false">
                	新增活動
                </a>
            </th>
          </tr>
          
          <tr>
            <th scope="row" >
            	<a href="activities_news_3.php" class="ui-btn" data-ajax="false">
            		我的活動
            	</a>
            </th>
          </tr>
          
          <tr>
            <th scope="row">&nbsp;</th>
          </tr>
          
          <tr>
            <th scope="row">
            	<font color="#0099FF" size="+2">榮譽殿堂</font>
            </th>
          </tr>
          
          <tr>
            <th scope="row">熱門夥伴</th>
          </tr>
          
          <tr>
            <th scope="row">評分</th>
          </tr>
          
          <tr>
            <th scope="row">&nbsp;</th>
          </tr>
          
          <tr>
            <th scope="row">
            	<font color="#0099FF" size="+2">個人運動台</font>
            </th>
          </tr>
          
          <tr>
            <th scope="row" >
                <a href="member_info.php" class="ui-btn" data-ajax="false">
                	<font size="+1">基本資料設定</font>
                </a>
            </th>
          </tr>
          
          <tr>
            <th scope="row" >歷史紀錄管理</th>
          </tr>
          
          <tr>
            <th scope="row" >
                <a href="test_update.php" class="ui-btn" data-ajax="false">
                	<font size="+1">多資料表更新測試</font>
                </a>

            </th>
          </tr>
          
          <tr>
            <th scope="row" >
            	<a href="<?php echo $logoutAction ?>" class="ui-btn">
                	<font size="+1">登出</font>
                </a>
            </th>
          </tr>
        </table>
	</div>
 </div>







<?php } else { ?><!--未登入狀態-->

<div id="home" data-role="page">

  
  <div role="main" class="ui-content">
    <div id="box" onselectstart="return false">
      <div id="box1" class="box-child"> <img src="https://www.google.com.tw/logos/doodles/2015/anna-atkins-216th-birthday-5710044637167616.3-hp.jpg" width="100%" height="100%"></div>
      <div id="box2" class="box-child">加油!!</div>
      <div id="box3" class="box-child">在一次</div>
      <div id="box4" class="box-child">登入</div>
    </div>
  </div>
  
  
  <div  data-position="fixed" data-role="footer" data-theme="b">
    <div data-role="navbar">
      <ul>
        <li id="b1">
          <a data-theme="b" class="ui-btn-active ui-state-persist">1</a>
        </li>
        <li id="b2">
          <a data-theme="b">2</a>
        </li>
        <li id="b3">
          <a data-theme="b">3</a>
        </li>
        <li id="b4">
          <a href="login.php">登入</a>
        </li>
      </ul>
    </div>
  </div>
</div>


<!--old page -->
<!--<div id="index" data-role="page" stlye="height:100%;" >
            
    <div id="header" data-position="fixed" data-role="header" data-theme="b">
        <h1>Android.Sport</h1>
    </div> 
                
                
            
    <div data-role="conter">
     
      <h5 align="center">將台灣運動賽事公告於此<p>尋找夥伴相約一同參賽</h5>
                               
      <div class="logo">
       
                <p align="center">
                <img src="images/111.png" alt="活動快訊"align="center" "width:45%" "height:45%"></p>
      </div>      
    </div>
        
                
    <div data-role="footer" data-position="fixed">
       <p "width:30%" "height:30%">
          <div data-role="navbar" data-iconpos="bottom">
                <div data-role="navbar">
                     <ul>
                        <li><a href="login.php" data-icon="home" class="ui-btn-active">登入</a></li>
                        <li><a href="member_add.php" data-icon="gear">加入會員</a></li>
                        
                     </ul></p>                                   
               </div>
          </div>
    </div>
    
</div>-->
<?php } ?>

</body>
</html>

<?php
mysql_free_result($Recordset1);

mysql_free_result($Recordset2);
?>
