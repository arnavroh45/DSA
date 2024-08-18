class Solution {
public:
    int numSteps(string s) {
        int carry = 0, count = 0; // to count the no of steps and to keep account of the carry.
        for(int i=s.length()-1;i>0;i--)
        {
            if((s[i]-'0')+carry==1) // if the number is odd then it takes 1 step more to convert it to even and change the carry as well.
            {
                count+=2;
                carry = 1;
            }
            else
                count+=1;
        }
        return count+carry;
        
    }
};

//1101 13
// 1110 14
// 0111 7 
// 1000 8
// 0100 4
// 0010 2
// 0001 1
