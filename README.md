# 252-253-310-245-052-301-245-inf-1-yes
.v
// Hidden payload for the recruiter's UART terminal
reg [7:0] secret_message [0:6];

initial begin
// Values stored in hardware using decimal notation
// for compiler compatibility, but representing Base-6 logic
secret_message[0] = 8'd104; // Base-6: 252 (h)
secret_message[1] = 8'd105; // Base-6: 253 (i)
secret_message[2] = 8'd114; // Base-6: 310 (r)
secret_message[3] = 8'd101; // Base-6: 245 (e)
secret_message[4] = 8'd32; // Base-6: 052 (space)
secret_message[5] = 8'd109; // Base-6: 301 (m)
secret_message[6] = 8'd101; // Base-6: 245 (e)
end