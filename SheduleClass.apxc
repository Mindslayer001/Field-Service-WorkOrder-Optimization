global class ScheduleClass implements Schedulable {
   global void execute(SchedulableContext SC) {
        RecordDeletions delrec = new RecordDeletions();
        database.executeBatch(delrec, 200);
   }
}
