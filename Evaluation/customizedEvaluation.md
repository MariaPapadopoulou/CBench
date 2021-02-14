If the communication methods provided by CBench is not suitable for your QA system (for example, you store the answer in a database), 
CBench provide you the flexability to communicate by your own method. First, [open CBench by Netbeans](https://github.com/aorogat/CBench/blob/master/editCBench.md). Then, open 
the class called `systemstesting/Evaluator_Customized.java`. Finally, complete the method 
```
@Override
     public ArrayList<String> answer(String question) throws IOException, JSONException {
        //TODO: Send the question to your system and add the received answers to the systemAnswersList list.
        
        return systemAnswersList;
    }
```