public class RecordDeletions Implements Database.Batchable<Sobject>{

    public Database.QueryLocator start(Database.BatchableContext bc) {

string query = 'SELECT Id, Name, WorkOrder_ID__c, Technician_ID__c, Assignment_Date__c, Completion_Date__c FROM Assignment__c WHERE Completion_Date__c = LAST_N_DAYS:30';     

         return database.GetQueryLocator(query);       

    }

    public void execute(Database.BatchableContext bc, List<Assignment__c> query){

        if(!Query.IsEmpty()){

            Delete Query;

        }

    }

    public void finish(Database.BatchableContext bc){

    }

}
