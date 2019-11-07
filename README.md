using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;
using UnityEngine.UI;

public class BtnMenu : MonoBehaviour
{


    private bool Pause = false;
    [SerializeField]
    private GameObject menupause;
    [SerializeField]
    public Button button;

    // Use this for initialization
    public void CarregarMenuD()
    {

        menupause.SetActive(true);

        /*if (menupause.activeInHierarchy)
        {
            MenuD();
        }
        else
        {
            Jogo();
        }

    } 

    public void Jogo()
    {
        menupause.SetActive(false);
        Time.timeScale = 1f;
    }

         public void MenuD()
         {
            menupause.SetActive(true);
           Time.timeScale = 0f;
            Pause = true;
        }*/
    }
