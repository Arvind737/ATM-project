# ATM-project
import datetime
now = datetime.datetime.now()
A=int(input("PLEASE ENTER YOUR CARD PIN :"))
print("*"*50)
print("\t1.Cash Withdrawal")
print("\t2.Balance Enquiry")
print("\t3.Pin Generate")
print("\t4.Mini Statement")
print("\t5.Exit")
print("*"*50)
TOTAL=100000
O=TOTAL-A
a=int(input("PLEASE SELECT OPTION:"))
match(a):
    case 1:
            print("-"*50)
            print("WHAT IS YOUR ACCOUNT TYPE")
            print("\t\t1.SAVING\t\t2.CURRENT")
            acaccount=int(input("CHOISE YOUR OPTION"))
            print("\tPlease WAIT YOUR TRUNCATION GETTING PROCESSING...")
            print("*"*50)
            print(A,"\tYOUR TRUNCATION GETS SUCCESSFUL..")
            print("."*50)
            print("\t\t YOU NEED SLIP")
            print('''\t
                 1.YES
                 2.NO
                    ''')
            H=int(input("ENTER YPUR OPTION"))
            print("-"*50)
            if(H==1):
                print("\t\t CANARA BANK")
                print("-"*50)
                print("\t\t BIDAR MAIN BRANCH")
                print("\tDATE\t\tTIME\t\tATM ID")
                print("\t{}\tCNRB123455".format(now))
                print("\tCARD NUMBER:\txxxxx4124")
                print("\tTXN NO:45154")
                print("\tRESPONSE CODE :454")
                print("-"*50)
                print("\tWITHDRAWAL AMOUNT RS.{}".format(A))
                print("-"*50)
                print("\tFROM A/C XXXXXXXXX4514")
                print("\t\t BAL RS.{}".format(O))
                print("\t\t MAKE YOUR PURCHASES WITH CANRA BANK")
                print("\t\tDEBIT CARD. EARN FREEDOM POINTS AND")
                print("\t\t GET FREE GIFTS.CALL 455554444")
                print("\t\tVist us at wwww.canrabank.com")
            if(H==2):
                print('''\t\t YOU SAVE ONE TREE 
                THANK YOU FOR VISTTING..''')
    case 2:
            print("WHAT IS YOUR ACCOUNT TYPE")
            print("\t\t1.SAVING\t\t2.CURRENT")
            acaccount=int(input("CHOISE YOUR OPTION"))
            print("AVLABIL BLANCE:{}".format(TOTAL))
            print("\t\t YOU NEED SLIP")
            print('''\t
                 1.YES
                 2.NO
                    ''')
            M=str(input("ENTR YOUR OPTION"))
            print("-"*50)
            if(M=="YES"):
                print("\t\t CANARA BANK")
                print("-"*50)
                print("\t\t BIDAR MAIN BRANCH")
                print("\tDATE\t\tTIME\t\tATM ID")
                print("\t{}\tCNRB123455".format(now))
                print("\tCARD NUMBER:\txxxxx4124")
                print("\tTXN NO:45154")
                print("\tRESPONSE CODE :454")
                print("-"*50)
                print("\t\tAVLIBALE BALANCE:{}".format(TOTAL))
                print("-"*50)
                print("\tFROM A/C XXXXXXXXX4514")
                print("\t\t MAKE YOUR PURCHASES WITH CANRA BANK")
                print("\t\tDEBIT CARD. EARN FREEDOM POINTS AND")
                print("\t\t GET FREE GIFTS.CALL 455554444")
                print("\t\tVist us at wwww.canrabank.com")
            if(M=="NO"):
                print('''\t\t YOU SAVE ONE TREE 
                THANK YOU FOR VISTTING..''')
    case 3:
            print("WHAT IS YOUR ACCOUNT TYPE")
            print("\t\t1.SAVING\t\t2.CURRENT")
            acaccount=int(input("CHOISE YOUR OPTION"))             
            b=int(input("PLEASE ENTER BANK ACCOUNT NUMBER"))
            print("."*50)
            B=int(input("PLEASE ENTER OTP SEND TO YOUR REGISTERED NUMBER:"))
            print("."*50)
            c=int(input("ENTER YOUR NEW PIN:"))
            print("."*50)
            print("YOUR PIN GENERATED SUCCESSFULLY...")
            print("*"*50)
            print("THANK YOU FOR VISITING...")
    case 4:
            print("\tYOU DON'T HAVE ANY TRUNCATION..")
            print("*"*50)
            print("\THANK YOU FOR VISITING")
    case 5:
            print("THANK YOU FOR VISITIG..")
