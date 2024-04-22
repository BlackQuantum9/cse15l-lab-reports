# Part 1
-------------------------------------
>
    import java.io.IOException;
    import java.net.URI;
    
    class Handler implements URLHandler {
        // The one bit of state on the server: a number that will be manipulated by
        // various requests.
        String output = "";
    
        public String handleRequest(URI url) {
            if (url.getPath().equals("/")) {
                return output;
            }
            else if (url.getPath().equals("/add-message")) {
                String query = url.getQuery();
                String user = "";
                String message = "";
                String[] inputs = query.split("&");
    
                for(String input : inputs){
                    String[] paras = input.split("=");
                    if(paras[0].equals("s")){
                        message = paras[1];
                    }
                    else if(paras[0].equals("user")){
                        user = paras[1];
                    }
                }
                if(!user.isEmpty() && !message.isEmpty()){
                    output += user + ": " + message + "\n";
                }
                return output;
            } 
            else {
                return "404 Not Found!";
            }
            // return output;
        }
    }
    
    class ChatServer {
        public static void main(String[] args) throws IOException {
            if(args.length == 0){
                System.out.println("Missing port number! Try any number between 1024 to 49151");
                return;
            }
    
            int port = Integer.parseInt(args[0]);
    
            Server.start(port, new Handler());
        }
    }

# Part 2

# Part 3
