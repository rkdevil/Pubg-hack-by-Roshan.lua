# Pubg-hack-by-Roshan.lua
gg.toast("馃嚠馃嚦馃憣Roshan-Hacker")
HOME = 1
function HOME()


 HM = gg.choice({
    "馃槑SNAPDRAGON", 
    "EXYNOS ",
    "WEAPONS SKINS", 
    "CHARACTER FEATURES", 
	"EXIT"
        }, nil,  "  PUBG 0.11 VIP HACK 馃挘馃Ж馃嚘馃嚞馃敨")


        
  if HM == 1 then
    SD()
  end 
  if HM == 2 then
    EXYNOS()
  end  
  if HM == 3 then
    OC()
  end
  if HM == 4 then
    LBLD() 
   end
   if HM == 5 then
    EXIT()
end 
   
  HOMEDM = -1
end









function LBLD()
  MIV = gg.multiChoice({
    "NO SHOCK 100%", 
    "Magic Bullet",    
    "No Grass", 
    "Black Sky  ", 
    "SitScope",
		"ON Fast Run 1 ",
	  "OFF Fast Run 1 ",
	  "NO GRASS",
	 "White Body EXYNOS",
	 "No Recoil OneClick (Game)",
 	 "No Recoil 100% (Pick Gun)",
	 "Antena COMPLETE BODY",
   "Antena VIP",
   "Antena ONLY IN 400M",
   "Antena Run & Stand",
   "Antenna Bag",
   "Flare Gun Antenna",
   "Walltrough",
    "Camera View",
	 "Speed And Jump",	 
	 "AUTO HEADSHOT",
   

    "😎🌈🇮🇳🇮🇳"
  }, nil,  "  PUBG 0.11 VIP Hacker Roshan")
  if MIV == nil then
  else
    if MIV[1] == true then NR() end
    if MIV[2] == true then MB() end
     if MIV[3] == true then NG() end
    if MIV[4] == true then BS() end
    if MIV[5] == true then HVON() end
	if MIV[6] == true then RUN1() end
	if MIV[7] == true then OFFRUN1() end 
	if MIV[8] == true then NOTGRASS() end
	if MIV[9] == true then WHITEBODY() end
	if MIV[10] == true then NRECOILALL() end
	if MIV[11] == true then NRECOILALL1() end
	if MIV[12] == true then      ATP()    end
    if MIV[13] == true then      ATNFIX()    end
    if MIV[14] == true then      ATN400()    end
    if MIV[15] == true then      ATR()    end
    if MIV[16] == true then      ATB()    end
  if MIV[17] == true then      FGA() end	
  if MIV[18] == true then      WT() end	
  if MIV[19] == true then      Cview() end	
  if MIV[20] == true then      SnJ() end	
  if MIV[21] == true then      ah() end
  if MIV[22] == true then      er() end
  
	if MIV[23] == true then     HOME()
    end
  end
end

function ah()

gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-460", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-560", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("450", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_BSS)
gg.searchNumber("2048D;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0.07", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Auto Headshot")
  
end


function er()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("220;178;15 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("1200", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Extended Review has been active")
end

function SnJ()
 gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;1;1;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("1.20", gg.TYPE_FLOAT)
gg.clearResults()
  
   gg.clearResults(850)
  gg.toast("Loading...")
  gg.searchNumber("1;35;443;0.5;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(850)
  print("Replaced: ", gg.editAll("0.5", gg.TYPE_FLOAT))
  gg.clearResults(850)
  gg.toast("High Jump has been active")
  
end


function Cview()
  gg.clearResults()
gg.searchNumber("-980.0F;0.30000001192F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-980", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-500", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Successful!")
  
end




function WT()
  gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5032462e-44F;10.0F;45.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("10", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Walltrough activated!")
gg.setVisible(false)
  
end

function FGA()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("0.7576~0.7579", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.7576~0.7579", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("99999", gg.TYPE_FLOAT)
  gg.toast("Flare Gun Antena activated!")
end


function ATB()
  gg.clearResults()
  gg.searchNumber("0.9378669858F;1.0F;0.61365610361F::55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(850)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Antenna Bag activated! ")
end

function ATR()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("18.38613319397F;0.53447723389F;3.42665576935F:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("6666", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("-1 076 364 016D;1 069 337 100D;1 091 058 328D;1 049 417 906D:13", gg.TYPE_DWORD)
  gg.searchNumber("-1 076 364 016", gg.TYPE_DWORD)
  gg.getResults(100)
  gg.editAll("1176255488", gg.TYPE_DWORD)
  gg.toast("Antena Run&Stand activated!")
end


function ATN400()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("0.99626296759", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResultCount()
  gg.getResults(50)
  gg.editAll("150", gg.TYPE_FLOAT)
  gg.getResults(50)
  gg.toast("Antena  400M activated!")
end



function ATNFIX()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(6)
  gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Antena Fix activated!")
end


function ATP()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("88.50576019287F;87.27782440186F;1F::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(7)
  gg.editAll("1.96875", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("1.96875F;1.96875F;-100.91194152832;1F::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("976", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("0.98900693655~0.98900723457;0.14786802232~0.14786840975;1.1920926e-7::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResultCount()
  gg.searchNumber("0.98900693655~0.98900723457", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("16000", gg.TYPE_FLOAT)
  gg.toast("Antena Pro activated!")
end





function NRECOILALL1()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.setVisible(false)
  gg.searchNumber("20000;5D;0.2~0.21999999881;1065353216D;1065353216D;0;53;30;1::33", gg.TYPE_FLOAT)
  gg.setVisible(false)
  gg.searchNumber("0.2~0.21999999881;1", gg.TYPE_FLOAT)
  gg.getResults(200)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("176293393;8F;9.5F;15F::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("176293393", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("1954047316;1970037078", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1954047316;1970037078", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.toast("No Recoil Done!")
end



function NRECOILALL()
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("50;200;0.5;40.0;0.3:512", 16, false, 536870912, 0, -1)
  gg.searchNumber("0.3", 16, false, 536870912, 0, -1)
  gg.getResults(20)
  gg.editAll("300", 16)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("1;10000D;100000:512", 16, false, 536870912, 0, -1)
  gg.searchNumber("1", 16, false, 536870912, 0, -1)
  gg.getResults(200)
  gg.editAll("0.001", 16)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("0.2~0.3;53;30;1::", 16)
  gg.searchNumber("0.2~0.3;1::", 16)
  gg.getResults(200)
  gg.editAll("1.4012985e-45", 16)
  gg.clearResults()
  gg.toast("No Recoil All weapons activated!")
end

function WHITEBODY()
gg.clearResults()
gg.toast('USE THIS IN TRAINING MODE THEN START GAME AGAIN')
gg.searchNumber('0.05499718338;1.0F', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll('999', gg.TYPE_FLOAT)
gg.toast('Cheat has been active')
end






function NOTGRASS()
gg.clearResults()
gg.toast('Being processed')
gg.searchNumber('8;1.2;0.8;1.5;0.8;1.5',gg.TYPE_FLOAT,false, gg.SIGN_EQUAL,0, -1)
gg.getResults(100)
gg.editAll('0', gg.TYPE_FLOAT)
gg.toast('Cheat has been active')
end



function RUN1()

gg.clearResults()
gg.searchNumber('1;1;1;0.0001;20;0.0005;0.4::50', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('1.1,2', gg.TYPE_FLOAT) 
gg.toast('Cheat has been active')
end 

function OFFRUN1()

gg.clearResults()
gg.searchNumber('1.1,2;1.1,2;1.1,2;0.0001;20;0.0005;0.4::50', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1,2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('1', gg.TYPE_FLOAT) 
gg.toast('Cheat has been active')
end 
 

 
 
 
function NR() 
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("1,084,227,584D;1D;0.64999997616F;1.2520827e-32F", 16, false, 536870912, 0, -1)
gg.searchNumber("1.2520827e-32", 16, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("1.4012985e-43", 16)
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("0.2~0.3;53;30;1::", 16, false, 536870912, 0, -1)
gg.searchNumber("0.2~0.3;1::", 16)
gg.getResults(200)
gg.editAll("1.4012985e-45", 16)
gg.clearResults()
gg.toast("Shockless shooting was activated")
end

function MB() 
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("20.51941871643;16;26::", 16, false, 536870912, 0, -1)
gg.searchNumber("16", 16, false, 536870912, 0, -1)
gg.getResults(3)
gg.editAll("101", 16)
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("20.51941871643;200;26::", 16, false, 536870912, 0, -1)
gg.searchNumber("26", 16, false, 536870912, 0, -1)
gg.getResults(3)
gg.editAll("-101", 16)
gg.clearResults()
gg.searchNumber("90.4850692749F;16", 16, false, 536870912, 0, -1)
gg.searchNumber("16", 16, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("88.01", 16)
gg.clearResults()
gg.toast("Bullet 閴侊拷")
end
 

 

function NG() 
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("252645121;252382983;201851904",gg.TYPE_DWORD,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.searchNumber("201,851,904",gg.TYPE_DWORD,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.getResults(1)
gg.editAll("0",gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("3856;201851904;16",gg.TYPE_DWORD,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.searchNumber("201,851,904",gg.TYPE_DWORD,false,gg.SIGN_FUZZY_EQUAL,0,-1)
 gg.getResults(2)
gg.editAll("0",gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("257;2131;0F~99999F;0::50",gg.TYPE_DWORD,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.searchNumber("0F~99999F",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.getResults(10)
gg.editAll("0",gg.TYPE_FLOAT)
gg.toast("No Grass Complete") 
end

function BS() 
gg.getResults(5000)
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.clearResults()
gg.searchNumber("100F;1F;1,008,981,770D:99",gg.TYPE_FLOAT,false)
gg.searchNumber("100",gg.TYPE_FLOAT,false)
gg.getResults(100)
gg.editAll("-90",gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Black Sky Complete") 
end


function HVON() 
gg.getResults(5000)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-0.67914116382599;-0.20633073151112;-0.68966287374496;9.49029350281;0.0064272880554199::",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)
gg.searchNumber("9.49029350281",gg.TYPE_FLOAT,false,gg.SIGN_FUZZY_EQUAL,0,-1)gg.getResults(500)
gg.editAll("333.0517578125",gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("SitScope ON") 
end


















 





function OC() 
  RF = gg.multiChoice({
    "Speed Shoot All Gun/ ",
    "M416 SKIN",
    "Scar SKIN ",
    "AKM SKIN",
    "M16 SKIN",
    "K98 SKIN",
    "UMP9 SKIN",
    "clears the wall",
    "fly",
    "run fast ",
    "Speed ┘hoot Arrows ",
    "Back"
  }, nil,  "  PUBG 0.11 VIP HACKER Roshan")
  if RF == nil then
  else
    if RF[1] == true then
      FBG()
    end
    if RF[2] == true then
      M4RF()
    end
    if RF[3] == true then
      SCRF()
    end
    if RF[4] == true then
      AKMRF()
    end
    if RF[5] == true then
      M16RF()
    end
    if RF[6] == true then
      AWMRF()
    end
    if RF[7] == true then
      JBKRF()
    end
    if RF[8] == true then
      M24RF()
    end
    if RF[9] == true then
      VSSRF()
    end
    if RF[10] == true then
      CFQRF()
    end
    if RF[11] == true then
      SZRF()
    end
    if RF[12] == true then
      HOME()
    end
  end
end
function FBG()
  gg.clearResults()
  gg.searchNumber("0.08;0.05;3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(99)
  gg.editAll("0.0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("DONE")
end
function M4RF()
  gg.clearResults()
gg.setRanges(32)
gg.searchNumber("10100400;101004", 4, false, 536870912, 0, -1)
gg.searchNumber("10100400", 4, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll("101004001", 4)
gg.toast("SKIN M4 ")
end
function SCRF()
  gg.clearResults()
gg.setRanges(32)
gg.searchNumber("10100300;101003", 4, false, 536870912, 0, -1)
gg.searchNumber("10100300", 4, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll("101003001", 4)
gg.toast("SKIN SCAL ")
end
function AKMRF()
  gg.clearResults()
gg.setRanges(32)
gg.searchNumber("10100100;101001", 4, false, 536870912, 0, -1)
gg.searchNumber("10100100", 4, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll("101001002", 4)
gg.toast("AKM SKIN !")
end
function M16RF()
  gg.clearResults()
gg.setRanges(32)
gg.searchNumber("10100200;101002", 4, false, 536870912, 0, -1)
gg.searchNumber("10100200", 4, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll("101002002", 4)
gg.toast("SKIN M16")
end
function AWMRF()
  gg.clearResults()
gg.setRanges(32)
gg.searchNumber("10300100;103001", 4, false, 536870912, 0, -1)
gg.searchNumber("10300100", 4, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll("103001001", 4)
gg.toast("SKIN K98 !")
end
function JBKRF()
  gg.clearResults()
gg.setRanges(32)
gg.searchNumber("10200200;102002", 4, false, 536870912, 0, -1)
gg.searchNumber("10200200", 4, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll("102002001", 4)
gg.toast("UMP9!")
end
function M24RF()
  gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5032462e-44F;10.0F;45.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("10", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.toast("DONE")
end
function VSSRF()
  gg.clearResults()
gg.setRanges(32)
gg.searchNumber("1.0F; -0.70710676908F;0.70710670948F; 64.0F; 1.793662e-43F;1.4012985e-45F; 1D; 1D ::512", 16, false, 536870912, 0, -1)
gg.searchNumber("1.4012985e-45", 16, false, 536870912, 0, -1)
gg.getResults(20)
gg.editAll("300", 16)
gg.clearResults()
gg.toast(" n")
end
function CFQRF()
  gg.clearResults()
gg.setRanges(16384)
gg.searchNumber("10.90734863281;0.00999999978", 16, false, 536870912, 0, -1)
gg.searchNumber("10.90734863281", 16, false, 536870912, 0, -1)
gg.getResults(300)
gg.editAll("10.3111", 16)
gg.clearResults()
gg.toast("DONE")
gg.setVisible(false)
  gg.toast("DONE")
end
function SZRF()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("16000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("200000", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("DONE")
end
function CNP()
gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("1954047316;1970037078", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1954047316;1970037078", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(99)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.toast(" 1")
 gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1,953,260,900;1,835,619,425", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1,953,260,900;1,835,619,425", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.toast(" 2")
gg.clearResults()
gg.setVisible(false)
gg.clearResults()
gg.clearResults()
gg.searchNumber("909391408;808923191::8", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultCount()
gg.toast("HI V G L OK")
gg.clearResults()
gg.searchNumber("257D;0~99999F;1D;0D::300", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultCount()
gg.searchNumber("0~9999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.toast("COMPLETE THE LAST BO FILE ")
end


















function SD() 
  SDC = gg.choice({
   "WALL HACK",
   "BODY COLOR",
   "BACK"
}, nil,  "  PUBG 0.11 VIP Hacker Roshan ")

if SDC == 1 then
    WH()
  end
  if SDC == 2 then
    BC()
  end
  if SDC == 33  then 
  HOME() 
end
end

function WH()
  WHC = gg.choice ({
    " SD PERFECT",
    " SD 415 ",
    " SD 425  ",
    " SD 435 - 620",
    " SD 636",
    " SD 625",
    " SD 660",
    " SD 835",
    " SD 820",
    " SD 845",
	" SD  WH Blink Island",
	" SD  WH scope Picked Weapon",
	" SD  WH Blink 100% fIX",
    "BACK"  
  },nil,"PUBG 0.11 MR NOOB GAMING")

  if WHC == 1 then whp() 
  end
   if WHC == 2  then wh1() 
  end
   if WHC == 3   then wh2() 
   end
  if WHC == 4  then wh3() 
  end
  if WHC == 5  then wh636()
   end
  if WHC == 6  then wh625()
   end
  if WHC == 7  then wh660() 
    end
 
   if WHC == 8  then wh835() 
   end
  if WHC == 9  then wh820()
   end
  if WHC == 10  then wh845() 
    end
	if WHC == 11  then whblink() 
    end
	if WHC == 12  then whscope() 
    end
	
	if WHC == 13  then whFIX() 
    end
	
    if WHC == 14  then SD() 
    end

  end



  function BC()
    BCC = gg.choice ({
      "Body RED",
      "ORANGE",
      "BLUE",
      "GREEN v�",
      "YELLOW �",
      "YELLOW",
      "PURPLE HDR",
      "RED HDR",
	  "RED COLOR+",
	  "RAINBOW COLOR ",
	  "ORANGES COLOR ",
	  "WhiteS COLOR ",
	  "Yellow COLOR ",
	  "Blue COLOR ",
	  "Green COLOR ",
	  "Pluto COLOR ",
	  "Shark COLOR ",
	   
      "BACK"  
    },nil,"PUBG 0.11 MR Roshan Kumar")


    
  if BCC == 1 then RED() 
end
 if BCC == 2  then ORANGE() 
end
 if BCC == 3   then BLUE() 
 end
if BCC == 4  then GREEN1() 
end
if BCC == 5  then GREEN2()
 end
if BCC == 6  then YELLOW()
 end
if BCC == 7  then PHR() 
  end
  if BCC == 8  then RHR() 
  end
    if BCC == 9  then REDC() 
  end
  if BCC == 10  then RAINBOW() 
  end
  if BCC == 11  then ORANGES() 
  end
  if BCC == 12  then WhiteS() 
  end
  if BCC == 13  then cYellow() 
  end
  if BCC == 14  then CBlue() 
  end
  if BCC == 15  then CGreen() 
  end
   if BCC == 16  then CPluto() 
  end
  if BCC == 17  then CShark() 
  end
   
   if BCC == 18  then bloodC() 
  end
  
  if BCC == 19  then Redsky() 
  end
  
  
   if BCC == 20  then Carc() 
  end
  
  if BCC == 21  then SD() 
  end

end


function whFIX()
gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("6.50000333786;1.1202013e-19;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("99999", gg.TYPE_FLOAT)
  gg.toast("Repair perspective flashing")
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("-1.0285578e-38;3.7615819e-37;2;-1;1;-127::300", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.toast("35%")
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.718519e-43F;3.7615819e-37;2;-1;1;-127::240", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.toast("50%")
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1.8947657e-40F;3.7615819e-37F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1.8947657e-40F;5.6896623e-29;3.7615819e-37F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.toast("80%")
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("200866D;2;-1;1;-127;0.24022650719;0.69314718246;0.00999999978::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.toast("Wait its is progress")
  
   gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.toast("Wait its is progress")
   gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("3.7615819e-37;1.3912552e-19;2.0;-1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;4.7961574e21;4.7408166e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;4.8699472e21;4.8699466e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;4.7777152e21;4.7777146e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Wait its is progress")
  
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.25;3.7500004768372;2.2500009536743;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -2)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.toast("SCRIPT EXCUTING  is successfully opened")
  
  
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("3.7615819e-37;1.3912552e-19;2.0;-1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;4.7961574e21;4.7408166e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;4.8699472e21;4.8699466e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;4.7777152e21;4.7777146e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.toast("Transparent open successfully")
   gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("65,536D;1.8945555e-40F;2.8130226e-40F;5.8013756e-42F;3.7615819e-37F;2.0F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("256D;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("200,866D; 2.718519e-43F; 3.7615819e-37F;2.0F; -1.0F; 1.0F; -127.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.toast("The ultimate  successfully DONE")
  end
  
  
  


function Carc()
 

gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("538968080D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("538968080", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("-999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Car color Activated!")

  end



function Redsky()
 

gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("671236105;1074792717;8200;1194363663;11::17", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("5", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Red Sky activated!")

  end


function bloodC()
 

gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("1.6815582e-44;1.1204998e-19;0.5;3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("444", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Blood Color activated!")

  end






function whscope()
 

gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("4.7223676e21;4.814603e21;3.7615819e-37;120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("2", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("3.7330591e-40;2.718519e-43;3.7615819e-37;120;0.00999999978", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("2", gg.TYPE_FLOAT)
gg.toast("Wallhack Fix Scope activated!")

  end




function CShark()
 

gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("252,776,218;253,824,770;252,248,832;201,851,904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("201851904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("17171717", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("252,907,268;50,335,498;3,874;201,851,904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("201851904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("17171717", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("254,283,524;253,038,346;254,018,304;201,851,904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("201851904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("17171717", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("252,776,217;50,335,490;3,846;201,851,904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("201851904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("17171717", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Shark activated!")

  end



function CPluto()
 
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("8,192D;256D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("4", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Pluto activated!")
  end


function CGreen()
 


gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("32769;768;-2134900730", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("32781", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Green activated!")
  end







function CBlue()
 


gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false)
gg.searchNumber("8200", gg.TYPE_DWORD, false)
gg.getResults(10)
gg.editAll("8202", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Blue activated!")
  end







function cYellow()
 

gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("256;8200;13::150", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("6", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Yellow activated!")

  end



function WhiteS()
 
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("3;1,081,612,800;278,200,320", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color White activated!")

  end


function ORANGES()
  gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("1.1490647e-41;1.0863203e-19::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.0863203e-19", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("1.0863203e-25", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Color Orange activated!")
  end



function RAINBOW()
  gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("1.1490647e-41;1.0863203e-19::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.0863203e-19", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("1.0863203e-25", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Color Rainbow activated!")
  end




function RED()
  gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("8,192D;256D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("7", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Body Red Success")
  end
  
  function REDC()
 gg.clearResults()
gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("7", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Red activated!")
  end
  function ORANGE()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1.1490647e-41;1.0863203e-19::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1.0863203e-19", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("1.0863203e-25", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Successful Activation")
  end
  function BLUE()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("589826", gg.TYPE_DWORD, false)
  gg.getResults(20050309)
  gg.editAll("666666", gg.TYPE_DWORD)
  gg.toast("Successful Activation")
  end
  function GREEN1()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("32769;768;-2134900730", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("32781", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("SUCCESS ACTIVATED")
  end
  function GREEN2()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.clearResults()
  gg.searchNumber("8201;8202;538968080:21", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0x0, 0xffffffffffffffff)
  gg.getResults(5)
  gg.editAll("8", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("538968071;8207:5", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8207", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0x0, 0xffffffffffffffff)
  gg.getResults(5)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("Successful Activation")
  end
  function YELLOW()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8200;1,080,035,591::512", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("Successful Activation")
  end
  function PHR()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("8,196D; 256D; 8,204D; 256D; 8,200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8,200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(12)
  gg.editAll("16", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("Successful Activation")
  end
  function RHR()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1,081,081,861;7;-2,146,435,049;8200::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("Successful Activation")
  end




  
 
function wh1()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_HEAP)
  gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT, false, 536870912, 0, -1)
  gg.clearResults()
  gg.searchNumber("3.1809475e-43;3.1949605e-43;2.0;3.2089735e-43:53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT, false, 536870912, 0, -1)
  gg.clearResults()
  gg.toast("SCRIPT DONE")
  end
  
  function wh2()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT, false, 536870912, 0, -1)
  gg.clearResults()
  gg.searchNumber("3.1809475e-43;3.1949605e-43;2.0;3.2089735e-43:53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT, false, 536870912, 0, -1)
  gg.clearResults()
  gg.toast("SCRIPT DONE")
  end
  function wh636()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("100%")
  gg.toast("SCRIPT DONE")
  end
  function wh3()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;-127.0F::520", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("SCRIPT DONE")
  end
  function wh625()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0F;4.7961574e21F;4.7408166e21F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.0F;4.8699472e21F;4.8699466e21F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.0F;4.7777152e21F;4.7777146e21F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("SCRIPT DONE")
  end
  function wh660()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("8E;2.5;6.0255834e-44::150", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-999", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.clearResults()
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("SCRIPT DONE")
  end
  function whp()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.toast("SCRIPT DONE")
  end
  
  function whblink()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.toast("SCRIPT DONE")
  end
  
  
  function wh835()
  gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("5.1097599e21;2.0;1.6623071e-19::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(30)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("-0.01000213623;2;-1;0;0.04000854492", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(30)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(30)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(131072)
    gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(30)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(30)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
  gg.toast("SCRIPT DONE")
  end
  function wh820()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("4.814603e21;3.5032462e-44;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("5.1848043e-44;-1.0285578e-38;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("304.00009155273;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.toast("SCRIPT DONE")
  end
  function wh845()
  gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("5.3680222e21;1.3312335e-43;1.3912563e-19;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("4.8146053e21;2.8866748e-43;1.3912556e-19;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("5.201992e21;4.4028356e-29;2.25000452995;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("4.9252857e21;6.488138e-40;4.9252863e21;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("1.0761972e-42;4.5920551e-41;-1.7632415e-38;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("1.0761972e-42;4.5923353e-41;-1.7632457e-38;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("5.3311276e21;1.3312335e-43;1.391256e-19;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber("4.8146041e21;2.8866748e-43;1.3912537e-19;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll("120", gg.TYPE_FLOAT)
    gg.clearResults()
  gg.toast("SCRIPT DONE")
  end




  function EXYNOS()
    EXYNO = gg.choice ({
      "White Body ",
      "Black Body ",
      "BACK"  
    },nil,"PUBG 0.11 MR Roshan Kumar")


    
  if EXYNO == 1 then WHITEBODY() 
end
 if EXYNO == 2  then BLACK() 
end
 
  if EXYNO == 3  then HOME() 
  end

end


  






function BLACK()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("0.05499718338;1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-9999", gg.TYPE_FLOAT)
  gg.toast("Body Black v1 has been active")
end

function WHITEBODY()
  gg.clearResults()
  gg.toast('USE THIS IN TRAINING MODE THEN START GAME AGAIN')
  gg.searchNumber('0.05499718338;1.0F', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll('999', gg.TYPE_FLOAT)
  gg.toast('Cheat has been active')
  end

function EXIT()
  os.exit()
end
while true do
  if gg.isVisible(true) then
    HOMEDM = 1
    gg.setVisible(false)
  end
  if HOMEDM == 1 then
    HOME()
  end
end



