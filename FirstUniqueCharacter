public class FirstUniqueCharacter {
    public static void main(String[] args) {
        String s = "leetcode";
        int[] count = new int[26];

        for (char ch : s.toCharArray()) {
            count[ch - 'a']++;
        }

        int answer = -1;
        for (int i = 0; i < s.length(); i++) {
            if (count[s.charAt(i) - 'a'] == 1) {
                answer = i;
                break;
            }
        }

        System.out.println(answer);
    }
}
