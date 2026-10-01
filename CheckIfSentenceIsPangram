public class CheckIfSentenceIsPangram {
    public static void main(String[] args) {
        String sentence = "thequickbrownfoxjumpsoverthelazydog";
        boolean[] seen = new boolean[26];

        for (char ch : sentence.toCharArray()) {
            if (ch >= 'a' && ch <= 'z') {
                seen[ch - 'a'] = true;
            }
        }

        boolean pangram = true;
        for (boolean value : seen) {
            if (!value) {
                pangram = false;
                break;
            }
        }

        System.out.println(pangram);
    }
}
