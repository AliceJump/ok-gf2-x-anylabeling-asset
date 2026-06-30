# ok-gf2-x-anylabeling-asset

## Downloads

![downloads](./assets/downloads.svg)

---

### 这是标注的源文件, 调用compress.py进行压缩后自动输出到assets/images下, 同时自动更新src/data/FeatureList.py

1. 使用 https://github.com/CVHub520/X-AnyLabeling 进行标注 `pip install x-anylabeling-cvhub`
2. cmd 运行 `xanylabeling` 软件打开 `project_dir`
3. 添加图片到 `project_dir`，使用软件进行标注
4. 运行 `compress.py`，cwd 需要是项目根目录，导出并替换（同时自动补充 `src/data/FeatureList.py` 的内容）
