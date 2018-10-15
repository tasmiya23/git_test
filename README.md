# git_test
import csv
cupid_match=['Date Issue raised','Issue Raised by','Pending with ','Status','Issue resolved Date']
with open('C:\Users\tasmiya.sana\Downloads\new', 'wb') as csvFile:  # creating the consolidation file
    fieldnames = cupid_match
    writer = csv.DictWriter(csvFile, fieldnames=fieldnames)
    writer.writeheader()
    print("Header Writen while creating")
    #for i in range(0,len(cupid_match)):
       
    writer.writerow({'UserName':"Huli"})
