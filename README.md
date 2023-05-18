# arvr


using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;

public class MoveSwitcher : MonoBehaviour
{
    // Start is called before the first frame update
    public void Start()
    {
        SceneManager.LoadScene("secondary");
    }

    // Update is called once per frame
public void Update()
    {
        SceneManager.LoadScene("main");

    }
}
