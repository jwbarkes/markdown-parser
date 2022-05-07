import static org.junit.Assert.*;
import java.nio.file.Files;
import java.nio.file.Path;
import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;

import javax.naming.spi.DirStateFactory.Result;

import org.junit.*;
public class MarkdownParseTest {
    @Test
    public void addition() {
        assertEquals(2, 1 + 1);
    }

    @Test
    public void test1() throws Exception{
        
        String content = Files.readString(Path.of("test-file.md"));
        ArrayList<String> results = MarkdownParse.getLinks(content);
        ArrayList<String> expect = new ArrayList<String>();
        expect.add("https://something.com");
        expect.add("some-thing.html");
        
        
        assertEquals(expect, results);
        
        
    }

    @Test
    public void test2() throws Exception{
        
        String content = Files.readString(Path.of("test-file2.md"));
        ArrayList<String> results = MarkdownParse.getLinks(content);
        ArrayList<String> expect = new ArrayList<String>();
        expect.add("https://something.com");
        expect.add("something.html");
       
        assertEquals(expect, results);
        
        
    }

    @Test
    public void test3() throws Exception{
        
        String content = Files.readString(Path.of("test-file3.md"));
        ArrayList<String> results = MarkdownParse.getLinks(content);
        ArrayList<String> expect = new ArrayList<String>();
        
        
        assertEquals(expect, results);
        
        
    }

    @Test
    public void test4() throws Exception{
        
        String content = Files.readString(Path.of("test-file4.md"));
        ArrayList<String> results = MarkdownParse.getLinks(content);
        ArrayList<String> expect = new ArrayList<String>();
        
        assertEquals(expect, results);
        
        
    }

    
    @Test
    public void test5() throws Exception{
        
        String content = Files.readString(Path.of("test-file5.md"));
        ArrayList<String> results = MarkdownParse.getLinks(content);
        ArrayList<String> expect = new ArrayList<String>();
    
        
        assertEquals(expect, results);
        
        
    }

      
    @Test
    public void test6() throws Exception{
        
        String content = Files.readString(Path.of("test-file6.md"));
        ArrayList<String> results = MarkdownParse.getLinks(content);
        ArrayList<String> expect = new ArrayList<String>();
    
        
        assertEquals(expect, results);
        
        
    }


   
}
