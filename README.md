# ssd_mobilenet_v2_coco_engine
This file is an object detection model for TensorRT.
<br style="font-size=0.5em">Source : Nvidia AI IoT Jetbot
<br><a href="https://drive.google.com/file/d/1Y76hPYgDdAm7F88a_HYv6kpS8Ysolgmt/view?usp=sharing">Download</a>

Recognizable List(ssd_mobilenet)      
<table>
<thead>
<tr>
<th>Index</th>
<th>Label</th>
</tr>
</thead>
<tbody>
</td>
</tr>
<tr>
<td>1</td>
<td>person</td>
</tr>
<tr>
<td>2</td>
<td>bicycle</td>
</tr>
<tr>
<td>3</td>
<td>car</td>
</tr>
<tr>
<td>4</td>
<td>motorcycle</td>
</tr>
<tr>
<td>5</td>
<td>airplane</td>
</tr>
<tr>
<td>6</td>
<td>bus</td>
</tr>
<tr>
<td>7</td>
<td>train</td>
</tr>
<tr>
<td>8</td>
<td>truck</td>
</tr>
<tr>
<td>9</td>
<td>boat</td>
</tr>
<tr>
<td>10</td>
<td>traffic light</td>
</tr>
<tr>
<td>11</td>
<td>fire hydrant</td>
</tr>
<tr>
<td>12</td>
<td></td>
</tr>
<tr>
<td>13</td>
<td>stop sign</td>
</tr>
<tr>
<td>14</td>
<td>parking meter</td>
</tr>
<tr>
<td>15</td>
<td>bench</td>
</tr>
<tr>
<td>16</td>
<td>bird</td>
</tr>
<tr>
<td>17</td>
<td>cat</td>
</tr>
<tr>
<td>18</td>
<td>dog</td>
</tr>
<tr>
<td>19</td>
<td>horse</td>
</tr>
<tr>
<td>20</td>
<td>sheep</td>
</tr>
<tr>
<td>21</td>
<td>cow</td>
</tr>
<tr>
<td>22</td>
<td>elephant</td>
</tr>
<tr>
<td>23</td>
<td>bear</td>
</tr>
<tr>
<td>24</td>
<td>zebra</td>
</tr>
<tr>
<td>25</td>
<td>giraffe</td>
</tr>
<tr>
<td>26</td>
<td></td>
</tr>
<tr>
<td>27</td>
<td>backpack</td>
</tr>
<tr>
<td>28</td>
<td>umbrella</td>
</tr>
<tr>
<td>29</td>
<td></td>
</tr>
<tr>
<td>30</td>
<td></td>
</tr>
<tr>
<td>31</td>
<td>handbag</td>
</tr>
<tr>
<td>32</td>
<td>tie</td>
</tr>
<tr>
<td>33</td>
<td>suitcase</td>
</tr>
<tr>
<td>34</td>
<td>frisbee</td>
</tr>
<tr>
<td>35</td>
<td>skis</td>
</tr>
<tr>
<td>36</td>
<td>snowboard</td>
</tr>
<tr>
<td>37</td>
<td>sports ball</td>
</tr>
<tr>
<td>38</td>
<td>kite</td>
</tr>
<tr>
<td>39</td>
<td>baseball bat</td>
</tr>
<tr>
<td>40</td>
<td>baseball glove</td>
</tr>
<tr>
<td>41</td>
<td>skateboard</td>
</tr>
<tr>
<td>42</td>
<td>surfboard</td>
</tr>
<tr>
<td>43</td>
<td>tennis racket</td>
</tr>
<tr>
<td>44</td>
<td>bottle</td>
</tr>
<tr>
<td>45</td>
<td></td>
</tr>
<tr>
<td>46</td>
<td>wine glass</td>
</tr>
<tr>
<td>47</td>
<td>cup</td>
</tr>
<tr>
<td>48</td>
<td>fork</td>
</tr>
<tr>
<td>49</td>
<td>knife</td>
</tr>
<tr>
<td>50</td>
<td>spoon</td>
</tr>
<tr>
<td>51</td>
<td>bowl</td>
</tr>
<tr>
<td>52</td>
<td>banana</td>
</tr>
<tr>
<td>53</td>
<td>apple</td>
</tr>
<tr>
<td>54</td>
<td>sandwich</td>
</tr>
<tr>
<td>55</td>
<td>orange</td>
</tr>
<tr>
<td>56</td>
<td>broccoli</td>
</tr>
<tr>
<td>57</td>
<td>carrot</td>
</tr>
<tr>
<td>58</td>
<td>hot dog</td>
</tr>
<tr>
<td>59</td>
<td>pizza</td>
</tr>
<tr>
<td>60</td>
<td>donut</td>
</tr>
<tr>
<td>61</td>
<td>cake</td>
</tr>
<tr>
<td>62</td>
<td>chair</td>
</tr>
<tr>
<td>63</td>
<td>couch</td>
</tr>
<tr>
<td>64</td>
<td>potted plant</td>
</tr>
<tr>
<td>65</td>
<td>bed</td>
</tr>
<tr>
<td>66</td>
<td></td>
</tr>
<tr>
<td>67</td>
<td>dining table</td>
</tr>
<tr>
<td>68</td>
<td></td>
</tr>
<tr>
<td>69</td>
<td></td>
</tr>
<tr>
<td>70</td>
<td>toilet</td>
</tr>
<tr>
<td>71</td>
<td></td>
</tr>
<tr>
<td>72</td>
<td>tv</td>
</tr>
<tr>
<td>73</td>
<td>laptop</td>
</tr>
<tr>
<td>74</td>
<td>mouse</td>
</tr>
<tr>
<td>75</td>
<td>remote</td>
</tr>
<tr>
<td>76</td>
<td>keyboard</td>
</tr>
<tr>
<td>77</td>
<td>cell phone</td>
</tr>
<tr>
<td>78</td>
<td>microwave</td>
</tr>
<tr>
<td>79</td>
<td>oven</td>
</tr>
<tr>
<td>80</td>
<td>toaster</td>
</tr>
<tr>
<td>81</td>
<td>sink</td>
</tr>
<tr>
<td>82</td>
<td>refrigerator</td>
</tr>
<tr>
<td>83</td>
<td></td>
</tr>
<tr>
<td>84</td>
<td>book</td>
</tr>
<tr>
<td>85</td>
<td>clock</td>
</tr>
<tr>
<td>86</td>
<td>vase</td>
</tr>
<tr>
<td>87</td>
<td>scissors</td>
</tr>
<tr>
<td>88</td>
<td>teddy bear</td>
</tr>
<tr>
<td>89</td>
<td>hair drier</td>
</tr>
<tr>
<td>90</td>
<td>toothbrush</td>
</tr>
</tbody>
</table>
